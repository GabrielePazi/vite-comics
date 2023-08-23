<script>
export default {
  components: {
    DcComics
  },
  data() {
    return {
      cardsArray: DcComics
    }
  }
};

import DcComics from '../assets/dc-comics.json'
</script>

<template>
  <div class="card-container d-flex justify-content-center flex-wrap gap-4 py-5">
    <div v-for="card in cardsArray" class="card rounded-0 bg-transparent border-0" style="width: 12rem;">
      <img :src="card.thumb" class="card-img-top rounded-0" alt="card.series">
      <div class="card-body px-0">
        <h6 class="text-white">{{ card.series }}</h6>
      </div>
    </div>

    <button class="btn btn-custom fw-semibold">LEARN MORE</button>
  </div>
</template>

<style lang="scss" scoped>
@use '../style/partials/button.scss' as *;

.card-container {
  img {
    aspect-ratio: 1/1;
  }

  button {
    width: 200px;
  }
}
</style>