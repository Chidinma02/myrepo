<template>
  <div id="app" class="app" :class="mode">
    <HelloWorld :mode="mode"></HelloWorld>

    <router-view />
    <FooTer></FooTer>
  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import FooTer from "./components/FooTer.vue";
export default {
  components: {
    HelloWorld,
    FooTer,
  },

  data() {
    return {
      // mode: "light",
    };
  },
};
</script>

<style>
/*.app.navi {
  background-color: white !important;
  color: black !important;
}
.dark.navi{
  background-color: black !important;
  color: white !important;
}*/
/*#app {
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
}*/
</style>