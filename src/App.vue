<script>
  export default {
    components: {
      TheHeader,
      TheShop,
      TheFooter
    }
  }
  import TheHeader from './components/TheHeader.vue';
  import TheShop from './components/TheShop.vue';
  import TheFooter from './components/TheFooter.vue';
</script>

<template>
  <TheHeader></TheHeader>

  <main class="bg-black">
    <div class="container">
      <h1 class="text-white py-5 ps-5">The content goes here</h1>
    </div>

    <TheShop></TheShop>
  </main>

  <TheFooter></TheFooter>
</template>

<style>
</style>
