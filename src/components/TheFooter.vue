<script>
export default {

};
</script>

<template>
  <footer>
    <div class="container-fluid">
      <div class="row py-4">
        <div class="col-6 col-md-2 mb-3">
          <h5 class="text-white fw-bolder">DC COMICS</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Characters</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Comics</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Movies</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">TV</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Games</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Videos</a></li>
            <li class="nav-item mb-5"><a href="#" class="nav-link p-0 text-secondary">News</a></li>
          </ul>

          <h5 class="text-white fw-bolder">SHOP</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Shop DC</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div class="col-6 col-md-2 mb-3">
          <h5 class="text-white fw-bolder">DC</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Terms Of Use</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Privacy Policy</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Ad Choices</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Advertising</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Jobs</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Subscriptions</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Talent Workshops</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">CPSC Certificates</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Ratings</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Shop Help</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Contact Us</a></li>
          </ul>
        </div>

        <div class="col-6 col-md-2 mb-3">
          <h5 class="text-white fw-bolder">SITES</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">DC</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">Mad Magazine</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">DC Kids</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">DC Universe</a></li>
            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-secondary">DC Power Vise</a></li>
          </ul>
        </div>
      </div>
    </div>

    <div class="social-container d-flex flex-wrap justify-content-between align-items-center py-3">
      <div>
        <button class="btn border-primary rounded-0 text-white fw-semibold">SIGN-UP NOW!</button>
      </div>

      <ul class="nav col-md-4 justify-content-end align-items-center list-unstyled d-flex">
        <div class="text-primary fw-bold fs-5">FOLLOW US</div>
        <li class="ms-3"><a class="text-white" href="#"><img src="../assets/images/footer-facebook.png"
              alt="facebook"></a></li>
        <li class="ms-3"><a class="text-white" href="#"><img src="../assets/images/footer-twitter.png" alt="twitter"></a>
        </li>
        <li class="ms-3"><a class="text-white" href="#"><img src="../assets/images/footer-youtube.png" alt="youtube"></a>
        </li>
        <li class="ms-3"><a class="text-white" href="#"><img src="../assets/images/footer-pinterest.png"
              alt="pinterest"></a></li>
        <li class="ms-3"><a class="text-white" href="#"><img src="../assets/images/footer-periscope.png"
              alt="periscope"></a></li>
      </ul>
    </div>
  </footer>
</template>

<style scoped lang="scss">
@use "../style/partials/variables.scss" as *;

footer {
  background-image: url(..//assets/images/footer-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;

  .row {
    background-image: url(../assets/images/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: 700px;
    background-size: 600px;
    margin-left: 8%;
  }

  .social-container {
    background-color: $color-footer-bg;
    padding: 0% 8%;
  }
}
</style>