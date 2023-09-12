<template>
  <div class="background-img">

    <div class="container-fluid">
      <div class="row">
        <div class="col-6">
          <div class="ms-5 mt-5">
            <h1 class="fs-5 text-white">Hi, I'm Andrew</h1>
            <h1 class="fs-3 text-white">A full-stack <span class="fs-1 text-warning">Software Developer</span> </h1>
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
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.background-img{
  background-image: url(https://images.hdqwalls.com/wallpapers/minimalistic-shapes-dark-neon-4k-54.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
  background-attachment: fixed;
}
</style>
