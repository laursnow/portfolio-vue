<template>
  <div class="container">
    <div class="main-border"></div>
    <div class="main">
      <div class="main-border bottom"></div>
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
  margin-top: 80px;
  float: right;
  margin-right: 15%;
}

.main {
  background-color: white;
  border: 1px solid black;
  height: 500px;
  width: 608px;
}

.main-border {
  background-image: url("../assets/border-main.png");
  background-position: center;
  background-repeat: no-repeat;
  padding: 0px;
  margin: 0px;
  width: 610px;
  height: 16px;
  position: relative;
}

.bottom {
  top: 500px;
  left: -1px;
}
</style>
