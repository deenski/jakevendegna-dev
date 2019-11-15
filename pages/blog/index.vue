<template>
  <div class="container">
    <div class="heading">
      <h1 class="title">
        My Thoughts
      </h1>
      <h2 class="subtitle">
        Articles
      </h2>
      <ul class="blog-links">
        <li class="links">
          <a href="blog/pipelines-first" class="links">A Pipelines-First Approach to DevOps</a>
        </li>
        <li class="links">
          <a href="blog/ha-traefik-consul-config" class="links">HA Traefik as a Kubernetes Ingress Controller With A Consul Backend</a>
        </li>
      </ul>
      <nuxt-child name="blog/pipelines-first" />
      <nuxt-child name="blog/ha-traefik-consul-config" />
    </div>
  </div>
</template>

<style>
  .blog-links {
    list-style-type: none;
  }
</style>
