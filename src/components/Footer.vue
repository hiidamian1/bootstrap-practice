<template>
  <div>
    <footer>
      <div class="container-fluid padding">
        <div class="row text-center">
          <div class="col-md-4">
            <img src="../assets/img/w3newbie.png">
            <hr class="light">
            <p>555-555-5555</p>
            <p>email@yeetmail.com</p>
            <p>100 Yeet Street</p>
            <p>Aberdeen, CA, 12345</p>
          </div>
          <div class="col-md-4">
            <hr class="light">
            <h5>Our Hours</h5>
            <hr class="light">
            <p>Monday: 9am - 5pm</p>
            <p>Saturday: 10am - 4pm</p>
            <p>Sunday: Closed</p>
          </div>
          <div class="col-md-4">
            <hr class="light">
            <h5>Service Area</h5>
            <hr class="light">
            <p>Aberdeen, CA, 12345</p>
            <p>Aberdeen, CA, 54321</p>
            <p>Aberdeen, CA, 23456</p>
            <p>Aberdeen, CA, 65432</p>
            <p>Aberdeen, CA, 34567</p>
          </div>
          <div class="col-12">
            <hr class="light-100">
            <h5>&copy; w3newbie.com</h5>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
footer {
  background-color: #3f3f3f;
  color: #d5d5d5;
  padding-top: 2rem;
}

.light {
  border-top: .0625rem solid #d5d5d5;
  width: 75%;
  margin-top: .8rem;
  margin-bottom: 1rem;
}

.light-100 {
  border-top: .0625rem solid #d5d5d5;
  width: 100%;
  margin-top: .8rem;
  margin-bottom: 1rem;
}

</style>
