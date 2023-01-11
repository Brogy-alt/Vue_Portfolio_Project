<template>
  
  <router-view/>
</template>

<style>

*,
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    cursor:pointer;
}

head,
main,
footer header,
body,
footer {
    min-width: 100%;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
