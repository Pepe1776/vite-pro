<script setup>
import { ref } from 'vue'
let counter = ref(0)

setInterval(() => {
  counter.value++
}, 1000)
</script>

<template>
  <div id="container">
    <header class="bg-black shadow" v-if="$route.meta.title">
      <div class="px-4 py-6 mx-auto max-w-7xl sm:px-6 lg:px-8">
        <h1
          id="title"
          @click="counter = 0"
          class="text-center text-3xl font-bold leading-tight text-gray-300"
        >
          {{ $route.meta.title }} / {{ counter }}
        </h1>
      </div>
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>
<style scoped>
@font-face {
  font-family: 'Alien';
  src: url('./assets/Sprykski.otf');
}
h1 {
  font-family: 'Alien';
}
</style>
