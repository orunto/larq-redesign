<script setup>
import Nav from './components/NavComponent.vue'
import Hero from './components/HeroSection.vue'
</script>

<template>

  <body class="fixed top-0 left-0 w-screen min-h-screen flex flex-col overflow-x-hidden z-50">

    <Nav />
    <Hero />
    <img src="/cap.png" alt="" class="w-[86px] h-15 absolute z-10 top-[123px]">
    <img src="/bottle.png" alt="" class="w-30 h-106 absolute z-10 top-[499px]">
  </body>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
