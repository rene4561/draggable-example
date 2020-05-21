<template>
  <div id="app">
    <header>
      <nav class="navigationMain"></nav>
    </header>
    <main>
      <nav class="navigationSide"></nav>
        <customize-navigationmenu-items class="setting"></customize-navigationmenu-items>
    </main>
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
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
body{
  margin: 0;
  padding: 0;
  padding-top: 61px;
}

#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#app .logo {
  text-align: center;
}

.navigationMain {
  display: block;
  position: fixed;
  top: 0;
  width: 100%;
  height: 61px;
  background-color: red;
}

main {
  padding: 0 60px 30px;
}
.navigationSide {
  background-color: blue;
  display: block;
  position: fixed;
  min-width: 300px;
  z-index: 10;
  top: 61px;
  left: 0;
  bottom: 0;
}
.setting{
  margin: 0 auto;
  max-width: 700px;
  padding: 35px 0;
      padding-left: 50px;
}
</style>
