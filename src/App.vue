<template>
  <router-view />
</template>

<style>
body {
  display: flex;
  justify-content: center;
  background: rgb(219, 219, 219);
  font-family: 'Prompt', sans-serif;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: -webkit-fill-available;
  max-width: 500px;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
