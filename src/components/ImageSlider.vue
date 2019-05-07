<template>
  <div>
    <div id="slides" class="carousel slide" data-ride="carousel">
      <ul class="carousel-indicators">
        <li data-target="#slides" data-slide-to="0" class="active"></li>
        <li data-target="#slides" data-slide-to="1"></li>
        <li data-target="#slides" data-slide-to="2"></li>
      </ul>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="../assets/img/background.png">
          <div class="carousel-caption">
            <h1 class="display-2">Bootstrap 4</h1>
            <h3>Complete Website Layout</h3>
            <button class="btn btn-outline-light btn-lg">VIEW DEMO</button>
            <button class="btn btn-primary btn-lg">Get Started</BUTTON>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/img/background2.png">
        </div>
        <div class="carousel-item">
          <img src="../assets/img/background3.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ImageSlider"
}
</script>

<style scoped>
  .carousel-inner img {
    width: 100%;
    height: 100%;
  }

  .carousel-caption {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
  }

  .carousel-caption h1 {
    font-size: 500%;
    text-transform: uppercase;
    text-shadow: .0625rem .0625rem .9375rem black;
  }

  .carousel-caption h3 {
    font-size: 200%;
    font-weight: 500;
    text-shadow: .0625rem .0625rem .625rem black;
    padding-bottom: 1rem;
  }

  @media (max-width: 768px) {
    .carousel-caption {
      top: 45%;
    }

    .carousel-caption h1 {
      font-size: 350%;
    }

    .carousel-caption h3 {
      font-size: 140%;
      font-weight: 400;
      padding-bottom: .2rem;
    }  

    .carousel-caption .btn {
      font-size: 95%;
      padding: .5rem .875rem; 
    }
  }  

  @media (max-width: 576px) {
    .carousel-caption {
      top: 40%;
    }

    .carousel-caption h1 {
      font-size: 250%;
    }

    .carousel-caption h3 {
      font-size: 110%;
    }  

    .carousel-caption .btn {
      font-size: 90%;
      padding: .25rem .5rem; 
    }

    .carousel-indicators {
      display: none;
    }
  }
</style>
