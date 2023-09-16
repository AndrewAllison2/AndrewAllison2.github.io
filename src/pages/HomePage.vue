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

      <div class="row">
        <h2 class="fs-1">APPLICATIONS</h2>
        <div>
          <div class="col-3">
            <div class="card" style="width: 18rem;">
              <img src="https://codeworks.blob.core.windows.net/public/assets/img/projects/AllSpicePoster.jpg" class="card-img-top" alt="AllSpice">
              <div class="card-body">
                <h5 class="card-title">AllSpice</h5>
                <p class="card-text">AllSpice is a full-stack recipe management application built with a VueJs front end and .Net back end. Users are able to create an account and login, browse recipes added by others and add their own. Instructions and ingredients can be added to recipes, and users can favorite recipes to save them.</p>
                <a href="https://github.com/AndrewAllison2/Allspice">View Github Repo</a>
              </div>
            </div>
          </div>
        </div>
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
