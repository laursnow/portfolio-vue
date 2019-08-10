<template>
  <div class="side-bar">
    <img src="../assets/feather.png" alt="feather vector by bimbimkha @ freepik" id="feather" />
    <div class="title-box">
      <h1>{{ h1 }}</h1>
      <h2>{{ h2 }}</h2>
    </div>
    <div class="side-divider"></div>
    <div class="about-box">
      <h3 id="liu">{{ about }}</h3>
      <p id="bree">{{ blurb }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
  props: {
    h1: String,
    h2: String,
    about: String,
    blurb: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.title-box {
  background-color: #25a3ad;
  width: 400px;
  height: 225px;
  padding: 10px 15px 10px 15px;
}

.about-box {
  background-color: #7163b6;
  width: 400px;
  height: 225px;
  padding: 10px 15px 10px 15px;
  text-align: center;
  font-size: 16px;
  color: white;
  font-weight: normal;
}

.side-divider {
  background-image: url("../assets/divider-side.png");
  height: 27px;
  background-color: #f0f0f0;
  padding: 3px 0px 3px 0px;
  background-position: center;
  background-repeat: no-repeat;
}

h1 {
  font-family: "Liu Jian Mao Cao", cursive;
  font-size: 32px;
  font-weight: bold;
  padding: 0px;
  margin: 13% 0 0 0;
}

h2 {
  font-family: "Bree Serif", serif;
  font-size: 68px;
  font-weight: bold;
  padding: 0px;
  margin: 0px;
  line-height: 68px;
}

h3 {
  font-size: 30px;
  line-height: 2px;
  padding: 0px;
  margin: 25px 0px 25px 0px;
}
#bree {
  font-family: "Bree Serif", serif;
}

#liu {
  font-family: "Liu Jian Mao Cao", cursive;
}

.side-bar {
  float: left;
  margin-top: 180px;
  text-align: center;
  margin-left: 15%;
}

#feather {
  position: absolute;
  height: 68%;
  left: 160px;
  top: 10px;
}
</style>
