<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/project">Project</router-link>
    <router-link to="/contact">Contact</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  width: 100%;
  z-index: 99;
  background: #191919;
}

nav a {
  font-weight: bold;
  color: #fff;
  opacity: 0.8;
  margin: 30px;
  font-size: 20px;
  text-decoration: none;
}

nav a.router-link-exact-active {
  opacity: 1;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  max-width: 1400px;
  display: block;
  margin: auto;
  min-height: 100vh;
  background: #191919;
  font-family: sans-serif;
}

@media screen and (max-width: 600px) {
  nav {
    padding: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  nav a {
    font-weight: bold;
    color: #fff;
    opacity: 0.8;
    margin: 10px;
    font-size: 20px;
    text-decoration: none;
  }
}
</style>
