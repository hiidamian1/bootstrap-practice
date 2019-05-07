<template>
  <div>
    <div class="container-fluid padding">
      <div class="row welcome text-center">
        <div class="col-12">
          <h1 class="display-4">
            Built with ease.
          </h1>
        </div>
        <hr>
        <div class="col-12">
          <p class="lead">
            Bootstrap is a free and open-source front-end library with HTML and CSS based designs.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Welcome"
}
</script>

<style scoped>
  .welcome {
    width: 75%;
    margin: 0 auto;
    padding-top: 2rem;
  }

  .welcome hr {
    border-top: .125rem solid #b4b4b4;
    width: 95%;
    margin-top: .3rem;
    margin-bottom: 1rem;
  }

  @media (max-width: 768px) {
    .display-4 {
      font-size: 200%;
    }  
  }  

  @media (max-width: 576px) {
    .display-4 {
      font-size: 160%;
    }  
  }
</style>
