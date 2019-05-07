<template>
  <div>
    <Navigation/>
    <ImageSlider/>
    <Jumbotron/>
    <Welcome/>
    <ThreeCols/>
    <TwoCols/>
    <FixedBackground/>
    <MeetTheTeam/>
    <Connect/>
    <Footer/>
  </div>
</template>

<script>
import Navigation from "./Navigation";
import ImageSlider from "./ImageSlider";
import Jumbotron from "./Jumbotron";
import Welcome from "./Welcome";
import ThreeCols from "./ThreeCols";
import TwoCols from "./TwoCols";
import FixedBackground from "./FixedBackground";
import MeetTheTeam from "./MeetTheTeam";
import Connect from "./Connect";
import Footer from "./Footer";

export default {
  name: 'Home',
  components: {
    Navigation,
    ImageSlider,
    Jumbotron,
    Welcome,
    ThreeCols,
    TwoCols,
    FixedBackground,
    MeetTheTeam,
    Connect,
    Footer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
