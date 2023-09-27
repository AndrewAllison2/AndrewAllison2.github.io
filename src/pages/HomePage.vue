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
        <!-- <div class="col-6">
          <div class="text-content-1 text-white ms-3 card elevation-4">
            <h1 class="text-center p-1">Devs And Dragons</h1>
            <div class="p-2">
              <p class="text-center">Devs and Dragons is a D&D campaign management application that helps players seamlessly manage and track their adventures in their game. Built by a team of five developers over the course of two weeks, this application was built with a VueJs front end and a NodeJS/Express back end. It integrates our own API as well as the official D&D API, which were both tested with Postman. It includes a wide array of technologies and features such as child routing to navigate and render important data while keeping focus on the game, intuitive and flexible UI based on a users status within their campaign, and authentication to track information and content you have created across all your adventures.
              </p>
              <p>
                Our team designed, created, and utilized our own UML, Figma mocks, and a Trello board throughout the build process. We also observed Agile and Scrum practices. We were faced with challeneges during the process, but strict project management, communication, and coordination allowed us to minimize merge conflicts and maximize our efficiency, which was a key factor in finishing the application within the time frame. 
              </p>
            </div>
          </div>
        </div>

        <div class="col-6 d-flex">
          <div class="pb-5">
            <img class="img-fluid dd-img" src='../assets/img/Screenshot (2).png' alt="Devs and Dragons">
          </div>
        </div> -->
      </div>

      <!-- SECTION DnD App -->
      <div class="row">
        <h1 class="text-center mb-3 text-white">Devs And Dragons</h1>
        <div class="col-4 dd-home-container">
          <div class="pb-5">
            <img class="img-fluid dd-home-img" src='../assets/img/Screenshot (2).png' alt="Devs and Dragons">
            <div class="overlay-dd-home">
              <p class=" home-text p-3">Devs and Dragons is a D&D campaign management application that helps players seamlessly manage and track their adventures in their game. Built by a team of five developers over the course of two weeks, this application was built with a VueJs front end and a NodeJS/Express back end. It integrates our own API as well as the official D&D API, which were both tested with Postman. This application utilizes a variey of technologies, an intutive and flexible UI, and was built with the potential for scaling in mind.
              </p>
            </div>
          </div>
        </div>
        <div class="col-4 dd-home-container">
          <div class="pb-5">
            <img class="img-fluid dd-home-img" src='../assets/img/Screenshot (2).png' alt="Devs and Dragons">
            <div class="overlay-dd-home">
              <p class=" home-text p-3">Devs and Dragons is a D&D campaign management application that helps players seamlessly manage and track their adventures in their game. Built by a team of five developers over the course of two weeks, this application was built with a VueJs front end and a NodeJS/Express back end. It integrates our own API as well as the official D&D API, which were both tested with Postman. This application utilizes a variey of technologies, an intutive and flexible UI, and was built with the potential for scaling in mind.
              </p>
            </div>
          </div>
        </div>
        <div class="col-4 dd-home-container">
          <div class="pb-5">
            <img class="img-fluid dd-home-img" src='../assets/img/Screenshot (2).png' alt="Devs and Dragons">
            <div class="overlay-dd-home">
              <p class=" dd-home-text p-3">Devs and Dragons is a D&D campaign management application that helps players seamlessly manage and track their adventures in their game. Built by a team of five developers over the course of two weeks, this application was built with a VueJs front end and a NodeJS/Express back end. It integrates our own API as well as the official D&D API, which were both tested with Postman. This application utilizes a variey of technologies, an intutive and flexible UI, and was built with the potential for scaling in mind.
              </p>
            </div>
          </div>
        </div>

        <a class="btn btn-primary dnd-btn" href="https://github.com/AndrewAllison2/devs_and_dragons" title="To GitHub/Devs&Dragons" role="button">View Code</a>
      </div>

      <!-- SECTION Keepr -->
      <div class="row">
        <h1 class="text-center mb-3 text-white">Keepr</h1>
        <div class="col-5 m-auto keepr-home-container">
          <div>
            <img class="img-fluid keepr-home" src="https://figmage.com/images/KndD8m4gDG7hjt1xgq5lo.jpg" alt="Keepr Picture">
            <div class="overlay-keepr-home">
              <p class="keepr-home-text">
                Keepr is a full stack web application similar to Pintrest. I built this over one week using a VueJs front end and a .Net/MySQL backend. It also incoorporates Auth0 to handle user authentication. The API was tested thoroughly with Postman, while the front end was tested for accessibility and best practices with Lighthouse. This application was also fully optimized for mobile screen sizes.
              </p>
            </div>
          </div>
        </div>
        <div class="col-5"></div>
      </div>

      <!-- SECTION AllSpice -->
      <div class="row">

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

.dnd-btn {
  width: 9em;
  position: relative;
  left: 43em;
  top: -1em;
}

.dd-home-container {
  position: relative;
}

.dd-home-img {
  object-fit: cover;
  border-radius: 5px;
}

.overlay-dd-home {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 10px;
  right: 0;
  height: 85%;
  width: 95.7%;
  opacity: 0;
  transition: .5s ease;
  background-color: #272727;
  border-radius: 5px;
}

.dd-home-container:hover .overlay-dd-home {
  opacity: 1;
}

.dd-home-text {
  color: white;
  position: absolute;
}

.keepr-home-container{
  position: relative;
}

.keepr-home {
  object-fit: cover;
  border-radius: 5px;
}

.overlay-keepr-home {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 10px;
  right: 0;
  height: 85%;
  width: 95.7%;
  opacity: 0;
  transition: .5s ease;
  background-color: #272727;
  border-radius: 5px;
}

.keepr-home-container:hover .overlay-keepr-home {
  opacity: 1;
}

.keepr-home-text {
  color: white;
  position:absolute;
}




</style>
