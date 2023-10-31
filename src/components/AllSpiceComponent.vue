<template>

  <div class="row mt-3" id="AllSpice">
      <div class="col-6">
        <div class="ms-4 mb-5">
          <a href="https://github.com/AndrewAllison2/Allspice">
            <img class="img-fluid allspice-img" src="https://codeworks.blob.core.windows.net/public/assets/img/projects/AllSpicePoster.jpg" alt="Keepr" title="View Github Repo">
          </a>
        </div>
      </div>

      <div class="col-6 mt-5">
        <div class="me-4 mb-3 text-white">
          <h3 class="text-center">AllSpice</h3>
          <p>A recipe management application built independently using a Vue.Js front end and a .Net/MySQL back end where users
            are able to add and view recipes
          </p>

          <p>Users can filter recipes by type, add or edit ingredients and instructions, and save their favorite recipes to
            their account</p>

            <p>This application's API was thoroughly tested with Postman, and has been optimized for mobile view.</p>
        </div>

        <div class="sm-h-line mt-4"></div>

        <div class="d-flex justify-content-between align-items-center mx-5 mt-4">
          <img class="img fluid vue-icon2" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid mysql-icon" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
          <img class="img fluid csharp-icon" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
          <img class="img fluid post-icon" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
        </div>

        </div>
      </div>

</template>


<script>
export default {
  setup(){
    return {}
  }
}
</script>


<style lang="scss" scoped>
.allspice-img {
  height: 25em;
  width: 100%;
  object-fit: cover;
}
.sm-h-line {
  height: 1px;
  background: white;
  width: 100%;
}
.vue-icon2 {
  height: 7.5em;
}
.mysql-icon {
  height: 8em;
}
.csharp-icon {
  height: 7em;
}
.post-icon{
  height: 7em
}
@media screen and (max-width: 769px){

}
</style>