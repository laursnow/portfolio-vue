<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <Sidebar
      h1="hello, this is my"
      h2="portfolio."
      about="Hi, I'm Lauren"
      blurb="I am a fullstack web developer based in Philadelphia, PA. I enjoy working with HTML, CSS, Javascript, jQuery, React/Redux, Vue, Node.js, Express, and Mongoose.

I previously worked as a project manager in the nonprofit sector. When I'm not coding, you can find me playing video games, wandering around Philly, searching for a +1 to my next concert, or travelling."
    />
    <Main />
  </div>
</template>

<script>
import Sidebar from "./components/Sidebar.vue";
import Main from "./components/Main.vue";

export default {
  name: "app",
  components: {
    Sidebar,
    Main
  }
};
</script>

<style>
body {
  box-sizing: border-box;
  background-color: #f0f0f0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
