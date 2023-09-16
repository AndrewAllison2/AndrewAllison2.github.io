<template>
          <div>
          <div class="col-12 d-flex">
            <div class="card" style="width: 22rem;">
              <img src="https://codeworks.blob.core.windows.net/public/assets/img/projects/AllSpicePoster.jpg" class="card-img-top" alt="AllSpice">
              <div class="card-body text-center">
                <h5 class="card-title">AllSpice</h5>
                <p class="card-text">AllSpice is a full-stack recipe management application built with a VueJs front end and .Net back end. Users are able to create an account and login, browse recipes added by others and add their own. Instructions and ingredients can be added to recipes, and users can favorite recipes to save them.</p>
                <a class="text-center" href="https://github.com/AndrewAllison2/Allspice">View Github Repo</a>
              </div>
            </div>

            <div class="card ms-2" style="width: 22rem;">
              <img src="https://figmage.com/images/KndD8m4gDG7hjt1xgq5lo.jpg" class="card-img-top" alt="Keepr">
              <div class="card-body text-center">
                <h5 class="card-title">Keepr</h5>
                <p class="card-text">Keepr is a pintrest style application where users can browse pictures called Keeps. Logged in users can create keeps and vaults, and are able to save Keeps within their public or private vaults. All users have a profile page where their vaults and keeps are displayed, and an account page where they can update their information and view keeps they've created.</p>
                <a class="text-center" href="https://github.com/AndrewAllison2/keepr">View Github Repo</a>
              </div>
            </div>

            <div class="card ms-2" style="width: 22rem;">
              <img src='../assets/img/Screenshot (2).png' class="card-img-top" alt="Devs and Dragons">
              <div class="card-body text-center">
                <h5 class="card-title">Devs and Dragons</h5>
                <p class="card-text">Devs and Dragons is a D&D Campaign management application that allows players to easily track and coordinate the status of their game. It was built in a team of five devolpers over the course of two weeks using a VueJs front end and NodeJs back end. This application also integrates the D&D api in the form of a search funtion present in each campaign.</p>
                <a class="text-center" href="https://github.com/AndrewAllison2/devs_and_dragons">View Github Repo</a>
              </div>
            </div>

            <div class="card ms-2" style="width: 22rem;">
              <img src='https://images.unsplash.com/photo-1612358405970-e1aeba9d76c2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1200&h=500&q=80' class="card-img-top" alt="Tower">
              <div class="card-body text-center">
                <h5 class="card-title">Tower</h5>
                <p class="card-text">Tower is a web application built with a VueJs front end and a NodeJs back end. It is centered around events called Towers. Users can get tickets to events they want to attend and leave comments on towers they are attending or are interested in.</p>
                <a class="text-center" href="https://github.com/AndrewAllison2/Tower">View Github Repo</a>
              </div>
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
img {
  height: 10em;
  object-fit: cover;
  padding: 2px;
}
</style>