<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

body {
  margin: 0;
  padding: 0;
  font: 400 0.625em/1.2 'Oswald', sans-serif;
  background-color: #000;
  color: #fff;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

h1,
h2 {
 margin: 0;
 padding: 0;
}

h1.wordmark {
 font: 400 6.0em/1 'Jomhuria', sans-serif;
 text-transform: uppercase;
}

h2 {
  font-size: 1.8em;
}

label {
  font-size: 1.6em;
}

</style>
