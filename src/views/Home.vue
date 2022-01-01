<script setup>
import ButtonRepo from '@/components/ButtonRepo.vue'
</script>

<template>
  <div id="cont">
    <a href="./about">
      <h2 class="transition ease-in-out hover:scale-110	 text-center text-7xl font-bold leading-tight animate-pulse">
        Nterface
      </h2></a>
    
    <h4 class="text-center text-4xl">Design => Deployment</h4>
    <div id="p" class="text-center text-2xl shadow-white-500">
      Full stack web devolopment using the Vue3 framework and Vite <br />
      to integrate custom tailored systems for each individual application
    </div>
  </div>
</template>

<style scoped>
@font-face {
  font-family: 'Marker';
  src: url('../assets/PermanentMarker-Regular.ttf');
}
#cont {
  height: 1000px;
  background-image: url('../assets/mac.jpg');
  background-size: 100%;
  background-repeat: no-repeat;
}
h2 {
  color: #3d5a80;
  font-family: 'Marker', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
h4 {
  margin: 5px 5px 5px 5px;
  color: #98c1d9;
  font-family: 'Marker', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
#p {
  margin: 15px 5px 5px 5px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  color: #e0fbfc;
}
</style>
