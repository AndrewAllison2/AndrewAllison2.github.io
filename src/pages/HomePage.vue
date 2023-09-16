<template>
  <div class="background-img">

    <div class="container-fluid">
      <div class="row">
        <div class="col-6">
          <div class="ms-5 mt-5">
            <h1 class="fs-5 text-white">Hi, I'm Andrew</h1>
            <h1 class="fs-3 text-white">A full-stack <span class="fs-1 text-warning">Software Developer</span> who loves designing intutive UI.</h1>
          </div>
        </div>

        <div class="col-6">
          <div>
            <img src="" alt="Andrew Allison">
          </div>
        </div>

      </div>

      <div class="row mt-5 text-center text-white">
        <h2 class="fs-1">SKILLS</h2>
      </div>

      <div class="row">
        <h2 class="fs-1 text-white text-center mb-5">APPLICATIONS</h2>
        <!-- <AppComponent /> -->
        <div class="col-12">

          <div class="pb-5">
            <img class="img-fluid dd-img" src='../assets/img/Screenshot (2).png' alt="Devs and Dragons">
          </div>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
import AppComponent from "../components/AppComponent.vue";

export default {
    setup() {
        return {};
    },
    components: { AppComponent }
}
</script>

<style scoped lang="scss">
.background-img{
  background-image: url(https://images.hdqwalls.com/wallpapers/minimalistic-shapes-dark-neon-4k-54.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}

.dd-img {
  width: 33em;
  object-fit: cover;
  position: relative;
  right: -4em;
}
</style>
