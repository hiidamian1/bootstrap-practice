<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home'

export default {
  name: 'app',
  components: {
    Home
  }
}
</script>

<style>
  @import "./assets/style.css";

  html, body {
    height: 100%;
    width: 100%;
    font-family: "Poppins", sans-serif;
    color: #222;
  }

  .btn-primary {
    background-color: #6648b1;
    border: .0625rem solid #6648b1;
  }

  .btn-primary:hover {
    background-color: #563d7c;
    border: .0625rem solid #563d7c;
  }

  .padding {
    padding-bottom: 2rem;
  }
</style>
