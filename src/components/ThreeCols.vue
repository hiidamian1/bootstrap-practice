<template>
  <div>
    <div class="container-fluid padding">
      <div class="row text-center padding">
        <div class="col-xs-12 col-sm-6 col-md-4">
          <i class="fas fa-code"></i>
          <h3>HTML5</h3>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <i class="fas fa-bold"></i>
          <h3>BOOTSTRAP 4</h3>
        </div>
        <div class="col-sm-12 col-md-4">
          <i class="fab fa-css3"></i>
          <h3>CSS3</h3>
        </div>
      </div>
      <hr class="my-4">
    </div>
  </div>
</template>

<script>
export default {
  name: "ThreeCols"
}
</script>

<style scoped>
.fa-code {
  color: #e54d26;
}

.fa-bold {
  color: #563d7c
}

.fa-css3 {
  color: #2163af
}

i {
  font-size: 4rem;
  margin: 1rem;
}

</style>
