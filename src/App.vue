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
  min-height: 100vh;
  min-width: 100vw;
  overflow: auto;
}

body {
  background-color: #fff;
  color: #000;
  font: 400 0.625em/1.2 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

h1,
h2 {
 margin: 0;
 padding: 0;
}

h1.wordmark {
 font: 400 8.0em/1 'Jomhuria', sans-serif;
 text-transform: uppercase;
}

p.p1 {
 font: 400 8.0em/0.8 'Jomhuria', sans-serif;
 text-transform: lowercase;
 margin: 0;
}

h2 {
  font-size: 2.0em;
  font-weight: 300;
  padding-bottom: 1em;
}

.highlight {
  color: #ff0000;
}

@media screen and (max-width: 600px) {
  body {
    font-size: 0.3125em;
  }

  h2 {
    font-size: 3.0em;
  }
}
</style>
