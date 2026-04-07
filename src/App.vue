<template>
  <nav id="nav">
  <h1 class="logo">Vue Pages</h1>

  <div class="links">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/quotes">Random Quotes</router-link>
    <router-link to="/contact">Contact</router-link>
  </div>
</nav>
    <div class="container">

    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

#nav {
  background-color: #2c3e50;
  color: white;
  padding: 20px 40px;

  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  margin: 0;
}
/* NAV LINKS */
.links a,
.links a:visited {
  color: white;
  text-decoration: none;
  font-weight: bold;
  margin-left: 20px;
}

.links a:hover {
  color: #ddd;
}

.links a.router-link-active {
  border-bottom: 2px solid white;
}

.container {
  padding: 40px;
}
</style>
