<template>
  <div>
    <div class="container-fluid padding">
      <div class="row welcome text-center">
        <div class="col-12">
          <h1 class="display-4">Meet the Team</h1>
        </div>
      </div>
      <hr>  
    </div>
    
    <Cards/>
    <hr class="my-4">
  </div>
</template>

<script>
import Cards from "./Cards";

export default {
  name: "MeetTheTeam",
  components: {
    Cards
  }
}
</script>

<style>

</style>
