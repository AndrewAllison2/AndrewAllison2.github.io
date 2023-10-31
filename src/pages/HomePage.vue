<template>
  <div class="container-fluid bg-black">

<!-- SECTION HOME -->
    <section id="home">
      <div class="background-img">
        <div class="row">
          <div class="mt-4 text-end">
            <!-- <GlowingIcons /> -->
          </div>
        </div>
    
        <div class="row mb-5">
          <div class="col-md-6 col-12 m-auto mt-5 me-5 pt-5 heading-section">
            <div class="mt-5 ms-2 text-black typewriter pt-5">
              <h1 class="fs-5 mt-5 text-shadow">Hi, I'm Andrew</h1>
                <h1 class="fs-5 text-shadow">A full-stack <span class="fs-1 text-info">Software Developer</span></h1>
            </div>
          </div>
        </div>
      </div>
    </section>


<!-- SECTION ABOUT -->

<!-- FIXME reorder sections on mobile -->
    <section id="about" class="about py-1">
      <div class="background-sec">
        <div class="row">
        <div class="col-md-5 col-12 text-center my-5 pt-5">
          <img class="img-fluid avatar" src="../assets/img/Professional-Photo.jpg" alt="Andrew Allison">
        </div>
  
        <div class="col-md-5 col-12 my-5 pt-5">
          <div class="text-white">
            <h2 class="mb-4" style='color:#f7a51b'>About Me</h2>
            <h5 class="mt-3 mb-3 font-italic">Hi, I'm Andrew!</h5>
            <p>I'm a passionate creator with a knack for design and problem solving. I enjoy designing and building intuitve UI's, as well as dealing with complex logic and data management. I thouroghly enjoy being challenged and working through problems to find creative solutions.</p>
            
            <p>Some of my hobbies include writing music, traveling to new places, and spending time outdoors with my wife and our golden retriever. I love learning new things and expanding my knoweldge in fields that I find interesting.</p>
          </div>
        </div>
      </div>
      </div>
    </section>

    <section>
      <div class="bg-black">
        <div class="row">
          <h1 class="text-center mt-3" style='color:#f7a51b'>My Skills</h1>
          <div class="col-12">
            <marquee class="mb-3 skills-icons">
              <img class="img- mx-2" style="height: 7em;" src="https://www.freeiconspng.com/thumbs/html5-icon/html5-icon-1.png" alt="HTML5" title="HTML5">
              <img class="img- mx-2" style="height: 7em;" src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" alt="CSS" title="CSS">
              <img class="img- mx-2" style="height: 7em;" src="https://static.vecteezy.com/system/resources/previews/027/127/463/original/javascript-logo-javascript-icon-transparent-free-png.png" alt="Javascript" title="Javascript">
              <img class="img  mx-2" style="height: 7em;" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
              <img class="img fluid mx-2" style="height: 6em;" src="https://static-00.iconduck.com/assets.00/node-js-icon-454x512-nztofx17.png" alt="NodeJs" title="NodeJS/Express">
              <img class="img fluid mx-2" style="height:6em;" src="https://icons-for-free.com/iconfiles/png/512/MongoDB-1329545826074381322.png" alt="MongoDB" title="MongoDB">
              <img class="img fluid mx-2" style="height: 6em;" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
              <img class="img fluid mx-2" style="height: 6em;" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
              <img class="img fluid mx-2" style="height: 6em;" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
              <img class="img fluid mx-2" style="height: 6em;" src="https://cdn.sanity.io/images/599r6htc/localized/46a76c802176eb17b04e12108de7e7e0f3736dc6-1024x1024.png?w=804&h=804&q=75&fit=max&auto=format" alt="Figma" title="Figma">
              <img class="img fluid mx-2" style="height: 6em;" src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" alt="Git" title="Git">
              <img class="img fluid mx-2" style="height: 5em;" src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/bootstrap-5-logo-icon.png" alt="Bootstrap" title="Bootstrap">
              <img class="img fluid mx-2" style="height: 5.5em;" src="https://static-00.iconduck.com/assets.00/auth0-icon-1832x2048-ewzjrdwk.png" alt="Auth0" title="Auth0">
              <img class="img fluid mx-2" style="height: 5.5em;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/512px-Visual_Studio_Code_1.35_icon.svg.png" alt="VSCode" title="VSCode">
            </marquee>
          </div>
        </div>
      </div>
    </section>


<!-- SECTION APPLICATIONS -->
<section id="applications" class="applications">
  <div class="background-third">
    <div class="row">
      <div class="col-md-8 col-12 m-auto my-5 pt-4">
        <h2 class="fs-1 app-text text-center">Applications</h2>
      </div>
    </div>

<!-- NOTE have it cycle through multiple imgs of apps here would be cool -->
    <div class="row mt-3" id="devs&dragons">
      <div class="col-md-6 col-12">
        <div class="ms-4 mb-5">
          <a href="https://github.com/AndrewAllison2/devs_and_dragons">
            <img class="img-fluid" src='../assets/img/DDScreenshot.png' alt="Devs & Dragons" title="View Github Repo">
          </a>
        </div>
      </div>

      <div class="col-md-6 col-12">
        <div class="me-4 mb-3 text-white">
          <h3 class="text-center mb-3">Devs & Dragons</h3>
          <p class="mb-4">A Dungeons & Dragons campaign management application built with a Vue.Js front
          end and an Express/NodeJs back end that allows players to stay connected and coordinate their games.
          </p>

          <p class="mb-4">This application was built by a team of five developers utilizing Scrum and Agile practices to coordinate our organization and communication throughout the build process.</p>

          <p class="mb-4">In addition to using MongoDB to store user data, this application also implements the D&D API to quickly and seamlessly provide
          users with information on the vast number of items within the game</p>
        </div>


        <div class="sm-h-line"></div>

        <div class="d-flex justify-content-between align-items-center mt-4 dd-icon-section">
          <img class="img fluid vue-icon" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid node-icon" src="https://static-00.iconduck.com/assets.00/node-js-icon-454x512-nztofx17.png" alt="NodeJs" title="NodeJS/Express">
          <img class="img fluid mongo-icon" src="https://icons-for-free.com/iconfiles/png/512/MongoDB-1329545826074381322.png" alt="MongoDB" title="MongoDB">
          <img class="img fluid post-icon" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
        </div>
      </div>
    </div>

        <div class="row">
          <div class="col-12 m-auto my-5">
            <div class="full-h-line"></div>
          </div>
        </div>

        <div class="row mt-3" id="keepr">
          
          <div class="col-md-6 col-12">
            <div class="ms-4 mb-3 text-white">
          <h3 class="text-center mb-3">Keepr</h3>
          <p>An application similar to Pintrest built in Vue.Js, .Net, and MySQL where users can manage their keeps and vaults, and
            share them with others.
          </p>

          <p>This application utilizes an Auth0 authenticator to verify and manage user accounts. The UI is updated
              accordingly based upon a user’s authentication.
              </p>

          <p>Built independently, I preformed API testing with Postman, accessibility/best practices testing with
            Lighthouse, and optimized the site for mobile view.
          </p>
          
          <p></p>

          
        </div>
        
        <div class="sm-h-line mt-4"></div>
        
        <div class="d-flex justify-content-between align-items-center mt-4 keepr-icon-section">
            <img class="img fluid vue-icon2 ms-2" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
            <img class="img fluid mysql-icon" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
            <img class="img fluid csharp-icon" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
            <img class="img fluid post-icon2" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
          </div>
          
        </div>
        <div class="col-md-6 col-12">
          <div class="me-4 mb-5">
            <a href="https://github.com/AndrewAllison2/keepr">
              <img class="img-fluid keepr-img" src="https://figmage.com/images/KndD8m4gDG7hjt1xgq5lo.jpg" alt="Keepr" title="View Github Repo">
            </a>
          </div>
        </div>
      </div>

        <div class="row">
          <div class="col-12 m-auto my-5">
            <div class="full-h-line"></div>
          </div>
        </div>

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
          <img class="img fluid post-icon2" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
        </div>

        </div>
      </div>

        <div class="row">
          <div class="col-12 m-auto mt-5">
            <div class="full-h-line"></div>
          </div>
        </div>
  </div>
</section>

    <!-- SECTION FORM -->
<section id="contact" class="contact">
  <ContactComponent />
</section>

  </div>
</template>

<script>
import ContactComponent from "../components/ContactComponent.vue";

// import assets from "scr/assets/img";



export default {
    setup() {
        return {
        // clearAllInputs(event) {
        //   var allInputs = document.querySelectorAll('input')
        //   allInputs.forEach(singleInput => singleInput.value = '')
        // }
        };
    },
    components: { ContactComponent }
}
</script>

<style scoped lang="scss">

.background-img{
  background-image: url('https://static.vecteezy.com/system/resources/previews/002/821/966/original/abstract-triangular-geometric-background-free-vector.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh;
}
.text-shadow{
  text-shadow: 1px 1px gray;
}
.h-line {
  height: 1px;
  width: 100%;
  background: black;
}

.background-sec {
  background: rgb(25,96,98);
background: linear-gradient(90deg, rgba(25,96,98,1) 0%, rgba(7,53,69,1) 35%, rgba(25,96,98,1) 100%);
height: 90vh;
}

.background-third {
  background: rgb(20,182,197);
background: linear-gradient(90deg, rgba(20,182,197,1) 0%, rgba(8,56,72,1) 50%, rgba(20,86,96,1) 100%);
}

.background-four{
  background-color: #efe8d8;
}

.full-h-line {
  height: 1px;
  width: 100%;
  background: white;
}

.sm-h-line {
  height: 1px;
  background: white;
  width: 100%;
}

.app-text{
  color: #f7a51b;
}
.dd-icon-section{
  margin-left: 3rem;
  margin-right: 3rem;
}

.html-icon {
  height: 8em;
}
.html-icon2 {
  height: 6em;
}

.css-icon {
  height: 8em;
}
.css-icon2 {
  height: 6em;
}

.js-icon {
  height: 8em;
}
.js-icon2 {
  height: 6em;
}

.mongo-icon{
  height: 7em;
}

.post-icon{
  height: 7em
}
.post-icon2{
  height: 7em
}

.vue-icon {
  height: 8em;
}
.vue-icon2 {
  height: 8em;
}

.node-icon {
  height: 7em;
}

.mysql-icon {
  height: 8em;
}

.csharp-icon {
  height: 7em;
}


.keepr-img {
  height: 25em;
  width: 100%;
  object-fit: cover;
}

.allspice-img {
  height: 25em;
  width: 100%;
  object-fit: cover;
}

.skills-icons{
  overflow-x: hidden;
  align-items: center;
}

.avatar {
  height: 25em;
  width: 25em;
  border-radius: 50%;
  object-fit: cover;
}

.typewriter h1 {
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .15em; /* Adjust as needed */
  animation: 
    typing 3.5s steps(40, end),
    blink-caret .75s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange; }
}

@media screen and (max-width: 769px) {
  .heading-section{
    margin-left: 0px;
  }
  .vue-icon{
    height: 5em;
    padding: 4px;
  }
  .node-icon{
    height: 5em;
    padding: 4px;
  }
  .mongo-icon{
    height: 5em;
    padding: 4px;
  }
  .post-icon{
    height: 5em;
    padding: 4px;
  }
  .dd-icon-section{
    margin-left: 1rem;
    margin-right: 1rem;
    
  }






.typewriter h1 {
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid orange; /* The typwriter cursor */
  white-space: wrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .10em; /* Adjust as needed */
  // animation: 
  //   typing 3.5s steps(40, end),
  //   blink-caret .75s step-end infinite;
}
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

}




</style>
