<template> 
  <div id="app">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.0/css/bulma.min.css">
    <nav class="navbar is-black" role="navigation" aria-label="main navigation">
        <div class="navbar-item is-tab is-expanded">
        <router-link to="/" class="title has-text-primary-dark">Home</router-link> 
      </div>
      <div class="navbar-item is-tab is-expanded">
        <router-link to="/about" class="title has-text-primary-dark">Black0ut_WP</router-link>
      </div>
        <router-view/>
    </nav>
  </div>
</template>

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
</style>
