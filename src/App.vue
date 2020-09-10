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
  font: 400 8.0em 'Jomhuria', sans-serif;
  text-transform: uppercase;
  padding-top: 0.2em;
  line-height: 50%;
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

  h1.wordmark {
    font-size: 9.0em;
  }

  p.p1 {
    font-size: 9.0em;
  }

  h2 {
    font-size: 3.0em;
  }
}
</style>
