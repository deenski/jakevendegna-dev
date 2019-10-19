<template>
  <div>
    <nuxt />
  </div>
</template>

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
</style>
