<script setup>
import ButtonRepo from '@/components/ButtonRepo.vue'
</script>

<template>
  <div id="cont">
    <h2 class="text-center text-7xl font-bold leading-tight animate-pulse">Nterface</h2>
    <h4 class="text-center text-4xl">Design => Deployment</h4>
    <div id="p" class=" text-center text-2xl shadow-white-500">
      Full stack web devolopment using the Vue3 framework and Vite <br /> to integrate
      custom tailored systems for each individual application
    </div>
  </div>
</template>

<style scoped>
#cont {
  height: 1000px;
  background-image: url('../assets/mac.jpg');
  background-size: 100%;
  background-repeat: no-repeat;
}
h2 {
  color: #133eff;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
h4 {
  color: #98c1d9;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
#p {
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  color: #e0fbfc;
}
</style>
