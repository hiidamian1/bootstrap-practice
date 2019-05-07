<template>
  <div>
    <button class="fun" data-toggle="collapse" data-target="#emoji">
      sik clik
    </button>
    <div id="emoji" class="collapse">
      <div class="container-fluid padding">
        <div class="row text-center">
          <div class="col-sm-6 col-md-3">
            <img src="../assets/img/gif/panda.gif" class="gif">
          </div>
          <div class="col-sm-6 col-md-3">
            <img src="../assets/img/gif/poo.gif" class="gif">
          </div>
          <div class="col-sm-6 col-md-3">
            <img src="../assets/img/gif/unicorn.gif" class="gif">
          </div>
          <div class="col-sm-6 col-md-3">
            <img src="../assets/img/gif/chicken.gif" class="gif">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Emojis"
}
</script>

<style scoped>
.fun {
  width: 100%;
  margin-bottom: 2rem;
}

.gif {
  max-width: 100%;
}
</style>
