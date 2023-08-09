<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="leftHeader">
      <RouterLink to="/"><i class="bi bi-apple" style="font-size: 35px;"></i></RouterLink>
    </div>  
    <div class="rightHeader">
      <RouterLink to="/About">公司簡介 About</RouterLink>
      <RouterLink to="/CertificationPatents">認證專利 Certification Patents</RouterLink>
      <RouterLink to="/Product">產品介紹 Product</RouterLink>
      <RouterLink to="/Contact">聯繫我們 Contact</RouterLink> 
    </div>
    <div class="otherLinks">
      <RouterLink to="/"><i class="bi bi-house-door-fill" style="font-size: 35px;"></i>首頁 ｜ HOME</RouterLink>
      <RouterLink to="/"><i class="bi bi-facebook" style="font-size: 35px;"></i></RouterLink>
      <RouterLink to="/"><i class="bi bi-line" style="font-size: 35px;"></i></RouterLink>
    </div>
  </nav>
  <RouterView />
</template>

<style scoped>
  .header {
  padding: 60px;
  font-family: "微軟正黑體";
  text-align: center;
  color: black;
  font-size: 30px;
  background: palevioletred;
}
.leftHeader{
  top:  10%;
  float: left;
  width: 10%;
  margin-left: 3%;
}
.rightHeader{
  width: 70%; 
  transform: translateY(-50%);
  display: flex;
  justify-content: space-evenly;
  margin-top: 3%;
}

.otherLinks{
  position: absolute;
  right: 0;
  width: 20%;
  float: right;
  display: flex;
  justify-content: space-evenly;
}
</style>
}