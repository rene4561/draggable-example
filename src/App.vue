<template>
  <div id="app">
    <customize-navigationmenu-items></customize-navigationmenu-items>
  </div>
</template>

<script>
import CustomizeNavigationmenuItems from "./components/CustomizeNavigationmenuItems";

export default {
  name: "app",
  components: {
    CustomizeNavigationmenuItems
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#app .logo {
  text-align: center;
}
</style>
