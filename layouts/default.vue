<template>
  <div>
    <nuxt />
    <logo />
    <navigation />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Navigation from '~/components/Nav.vue'

export default {
  components: {
    Logo,
    Navigation
  }
}
</script>

<style>
html {
  font-family: Consolas, monaco, monospace;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--white {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #ffffff;
  color: #eeeeee;
  text-decoration: none;
  padding: 10px 30px;
}

.button--white:hover {
  color: #000;
  background-color: #ffffff;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #fff;
  color: #eee;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #0077b5;
}

.button--coral {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #ff6f61;
  color: #ff6f61;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--coral:hover {
  color: #fff;
  background-color: #ff6f61;
  border: 1px solid #fff;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #47555e;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #eeeeee;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #fff;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.caption {
  font-weight: 100;
  font-size: 28px;
  color: #fff;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.article {
  padding-top: 15px;
  font-weight: 100;
  font-size: 24px;
  color: #fff;
  word-spacing: 5px;
  justify-content: left;
  align-items: left;
  text-align: left;
  display: flex;
}
</style>
