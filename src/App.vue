<script setup>
</script>

<template>
  <header>
  <div id="header-info">
    <div id="header-info-text">

      <div>
        <p class="info-text">
        Get 25% off buying the entire capsule collection
        </p>
      </div>
      <div>
      <p style="opacity: 0.3; color: #FFF;">
      |
      </p>
      </div>

      <div>
        <p class="info-text">
        Subscribe to us and get 15% off your first order
        </p>
      </div>

    </div>
  </div>
  
  <div id="start-block">
  </div>
  </header>

  <main></main>
  <footer></footer>
</template>

<style scoped>

@import "./assets/base.css";

#main-img{
  width: 100%;
  height: 100%;
}

#start-block{
  width: 1920px;
  height: 920px;
  background-image: url("./assets/images/main-img.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 0px -360px;
  background-color: black;
}

#header-info{
  width: 1920px;
  height: 46px;
  background-color: #50735F;
  display: flex;
  justify-content: center;
}

#header-info-text{
  margin-top: 15px;
  width: 649px;
  height: 14px;
  text-align: center;
  display: flex;
}

.info-text{
  color: #FFF;
  font-family: 'Overpass', sans-serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 100%; /* 14px */

}
</style>
