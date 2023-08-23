<script>
export default {

};
</script>

<template>
  <div class="jumbotron-custom w-100 position-relative">
    <button class="btn btn-custom fw-bold fs-5 position-absolute px-4">CURRENT SERIES</button>
  </div>
</template>

<style lang="scss" scoped>
@use '../style/partials/button.scss' as *;

.jumbotron-custom {
  background-image: url(../assets/images/jumbotron.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  height: 300px;

  .btn {
    bottom: 0;
    left: 8%;
    transform: translateY(50%);
  }
}
</style>