<template>
  <div class="container">
    <div class="main-border"></div>
    <div class="main">
      <div class="main-border"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
  props: {
    projects: null,
    contact: null
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  margin-top: 100px;
  float: right;
  margin-right: 15%;
  width: 500px;
}

.main {
  background-color: white;
  border: 1px solid black;
  height: 500px;
}

.main-border {
  background-image: url("");
  background-position: center;
  background-repeat: no-repeat;
}
</style>
