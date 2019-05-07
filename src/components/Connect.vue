<template>
  <div>
    <div class="container-fluid padding">
      <div class="row text-center padding">
        <div class="col-12">
          <h2>Connect</h2>
        </div>
        <div class="col-12 social padding">
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-google-plus-g"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-youtube"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Connect"
}
</script>

<style scoped>
.social a{
  font-size: 4.5rem;
  padding: 3rem;
}

.social i:hover {
  color: #d5d5d5;
}

.fa-facebook {
  color: #3b5998;
}
.fa-twitter {
  color: #00aced;
}
.fa-google-plus-g {
  color: #dd4b39;
}
.fa-instagram {
  color: #517fa4;
}
.fa-youtube {
  color: #bb0000;
}

@media (max-width: 992px) {
  .social a {
    font-size: 4rem;
    padding: 2rem;
  }
} 

@media (max-width: 768px) {
  .social a {
    font-size: 2.5rem;
    padding: 1.2rem;
  }
} 

@media (max-width: 576px) {
  .social a {
    font-size: 2rem;
    padding: .7rem;
  }
} 
</style>
