<template>
  <div id="nav">
<AppHeader />
<Register />
    <router-link to="/"></router-link> 
    <!-- <router-link :to="{ name: 'About' }">About</router-link> -->
    <!-- <router-link :to="{ name: 'Jobs' }">Jobs</router-link> -->
  <router-view />
 </div>
  <!-- <router-view /> -->
</template>

<script>
import Register from "./pages/Register.vue"
import AppHeader from "./components/AppHeader.vue";
export default {
  name: "app",
  components: {
    AppHeader,
Register,
  },
};
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
} */
/* 
#nav {

  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  padding: 10px;
  border-radius: 4px;
}

#nav a.router-link-exact-active {
  color: white;
  background: crimson; */
/* } */
</style>
