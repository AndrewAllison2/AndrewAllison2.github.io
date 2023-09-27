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
            <!-- <img class="avatar" src="../assets/img/Professional Photo.jpg" alt="Andrew Allison"> -->
          </div>
        </div>

      </div>

      <div class="row mt-5 text-center text-white">
        <h2 class="fs-1">SKILLS</h2>
      </div>

      <div class="row">
        <h2 class="fs-1 text-white text-center mb-5">APPLICATIONS</h2>
        <!-- <AppComponent /> -->
        <div class="col-6 d-flex">
          <div class="pb-5">
            <img class="img-fluid dd-img ms-4" src='../assets/img/Screenshot (2).png' alt="Devs and Dragons">
          </div>
        </div>
        
        <div class="col-6">
          <div class="text-content-1 text-white ms-5 card elevation-4">
            <h1 class="text-center p-1">Devs And Dragons</h1>
            <div class="p-2">
              <p class="text-center">Devs and Dragons is a D&D campaign management application that helps players seamlessly manage and track their adventures in their game. Built by a team of five developers over the course of two weeks, this application was built with a VueJs front end and a NodeJS/Express back end. It integrates our own API as well as the official D&D API, which were both tested with Postman. It includes a wide array of technologies and features such as child routing to navigate and render important data while keeping focus on the game, intuitive and flexible UI based on a users status within their campaign, and account information tracking content you have created across all your adventures.
              </p>
              <p>
                Our team designed, created, and utilized our own UML, Figma mocks, and a Trello board throughout the build process. We also observed Agile and Scrum practices. We were faced with challeneges throughout the process, but strict project management, communication, and coordination allowed us to minimize merge conflicts and maximize our efficiency, which was a key factor in finishing the application within the time frame. 
              </p>
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
        return {};
    },

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

.avatar {
  object-fit: cover;
  
}

.dd-img {
  // width: 33em;
  object-fit: cover;
  border-radius: 2px;
  // position: relative;
  // right: -4em;
}

.text-content-1 {
  background-color: rgba(63, 63, 63, 0.418);
  
  
  color: white;
}
</style>
