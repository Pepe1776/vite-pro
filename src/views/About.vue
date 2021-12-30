<script setup>
import ButtonRepo from '@/components/ButtonRepo.vue'
</script>

<template>
  <div class="bg-gray-50" id="cont2">
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
        id="about"
        class="
          text-3xl
          font-extrabold
          leading-9
          tracking-tight
          text-blue-300
          sm:text-4xl sm:leading-10
        "
      >
        <span id="about"> Design => Deployment</span>
        <br />
        <span class="text-gray-200"
          >Crestron Ui/Ux integrations tailormade fore each enviroment</span
        >
      </h2>
      <div class="flex mt-8 lg:flex-shrink-0 lg:mt-0">
        <div class="inline-flex rounded-md shadow">
          <router-link
            to="/"
            id="back"
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
              bg-blue-600
              border border-transparent
              rounded-md
              hover:bg-blue-500
              focus:outline-none
            "
            >Back Home</router-link
          >
        </div>
        <ButtonRepo />
      </div>
    </div>
  </div>
</template>
<style>
@font-face {
  font-family: 'Marker';
  src: url('../assets/PermanentMarker-Regular.ttf');
}

#cont2 {
  background-image: url('../assets/tab.jpg');
  background-size: 150rem;
  height: 855px;
}
#back {
  font-family: 'Marker';
}
</style>
