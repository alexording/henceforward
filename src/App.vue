<template>
  <router-view/>
</template>

<style lang="scss">
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  overflow: auto;
}

body {
  background-color: #fff;
  color: #000;
  font: 400 0.625em/1.2 'Merriweather', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

h1,
h2,
p {
 margin: 0;
 padding: 0;
}
</style>
