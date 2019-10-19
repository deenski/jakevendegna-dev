<template>
  <div class="nav">
    <nav>
      <router-link id="home" to="/" class="button--coral">
        > Home
      </router-link>
      <router-link to="/about" class="button--coral">
        > About
      </router-link>
    </nav>
  </div>
</template>

<style>

.nav {
  position: absolute;
  top: 2vh;
  left: 30vh;
  width: 75vh;
  font-family: Consolas, monaco, monospace;
}

</style>
