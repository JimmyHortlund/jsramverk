<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/reports">Reports</router-link>
    </div>

    <router-view/>
    <div id="footer">
      <router-link to="/">Apa</router-link> |
      <router-link to="/reports">Monkey</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
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

#footer {
  padding: 30px;
}

#footer a {
  font-weight: bold;
  color: #2c3e50;
}

#footer a.router-link-exact-active {
  color: #42b983;
}
</style>
