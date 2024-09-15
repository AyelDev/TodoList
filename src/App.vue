<template>
  <nav class="sidenav">
    <router-link to="/">Home</router-link><br>
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  position: relative;
}

nav {
  padding: 20px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

.sidenav{
  background-color: lightblue;
  height: 80vh;
  width: 15rem;
  border-radius: 2rem;
}

</style>
