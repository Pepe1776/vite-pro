<script setup>
import ButtonRepo from '@/components/ButtonRepo.vue'
</script>

<template>
  <div class="bg-gray-50" id="cont">
    <div
      class="
        max-w-screen-xl
        px-4
        py-12
        mx-auto
        sm:px-6
        lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-between
      "
    >
      <h2
        class="
          text-3xl
          font-extrabold
          leading-9
          tracking-tight
          text-gray-900
          sm:text-4xl sm:leading-10
        "
      >
        Full Stack Devolopment
        <br />
        <span class="text-lime-600">Vite + Vue 3 + Tailwind CSS + Node + Firebase</span>
      </h2>
      <div class="flex mt-8 lg:flex-shrink-0 lg:mt-0">
        <div class="inline-flex rounded-md shadow">
          <router-link
            to="/about"
            class="
              inline-flex
              items-center
              justify-center
              px-5
              py-3
              text-base
              font-medium
              leading-6
              text-white
              transition
              duration-150
              ease-in-out
              bg-lime-600
              border border-transparent
              rounded-md
              hover:bg-green-700
              focus:outline-none
            "
            >More Info</router-link
          >
        </div>
        <ButtonRepo />
      </div>
    </div>
  </div>
</template>

<style>
#cont {
  background-image: url('../assets/wht2.jpg');
  background-size: 150rem;
}
</style>
