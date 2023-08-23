<script>
  export default {
    components: {
      TheHeader,
      TheShop,
      TheFooter,
      TheJumbotron,
      TheAlbum
    }
  }
  import TheHeader from './components/TheHeader.vue';
  import TheShop from './components/TheShop.vue';
  import TheFooter from './components/TheFooter.vue';
  import TheJumbotron from './components/TheJumbotron.vue'
  import TheAlbum from './components/TheAlbum.vue'
</script>

<template>
  <TheHeader></TheHeader>

  <TheJumbotron></TheJumbotron>
  <main>
    <div class="container">

      <TheAlbum></TheAlbum>
      
    </div>

    <TheShop></TheShop>
  </main>

  <TheFooter></TheFooter>
</template>

<style>

main {
  background-color: rgb(28, 28, 28);
}
</style>
