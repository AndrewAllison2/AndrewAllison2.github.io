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
          <div class="col-6 m-auto mt-5 me-5 pt-5">
            <div class="mt-5 ms-2 text-black typewriter pt-5">
              <h1 class="fs-5 mt-5 text-shadow">Hi, I'm Andrew</h1>
                <h1 class="fs-5 text-shadow">A full-stack <span class="fs-1 text-info">Software Developer</span></h1>
            </div>
          </div>
        </div>
      </div>
    </section>


<!-- SECTION ABOUT -->
    <section id="about">
      <div class="background-sec">
        <div class="row">
        <div class="col-5 text-center my-5">
          <img class="img-fluid avatar" src="../assets/img/Professional Photo.jpg" alt="Andrew Allison">
        </div>
  
        <div class="col-5 my-5">
          <div class="text-white">
            <h2 class="mb-4">About Me</h2>
            <h5 class="mt-3 mb-3 font-italic">Hi, I'm Andrew!</h5>
            <p>I'm a passionate creator with a knack for design and problem solving. I enjoy designing and building intuitve UI's, as well as dealing with complex logic and data management. I thouroghly enjoy being challenged and working through problems to find creative solutions.</p>
            
            <p>Some of my hobbies include writing music, traveling to new places, and spending time outdoors with my wife and our golden retriever. I love learning new things and expanding my knoweldge in fields that I find interesting.</p>
          </div>
        </div>
      </div>
      </div>
    </section>


<!-- SECTION APPLICATIONS -->
<section id="#applications">
  <div class="background-third">
    <div class="row">
      <div class="col-8 m-auto my-5">
        <h2 class="fs-1 app-text text-center">Applications</h2>
      </div>
    </div>

<!-- NOTE have it cycle through multiple imgs of apps here would be cool -->
    <div class="row mt-3" id="devs&dragons">
      <div class="col-6">
        <div class="ms-4 mb-5">
          <img class="img-fluid" src="../assets/img/Screenshot (2).png" alt="Devs & Dragons">
        </div>
      </div>

      <div class="col-6">
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

        <div class="d-flex justify-content-between align-items-center mx-5 mt-4">
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
          
          <div class="col-6">
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
        
        <div class="d-flex justify-content-between align-items-center mx-5 mt-4">
            <img class="img fluid vue-icon2" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
            <img class="img fluid mysql-icon" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
            <img class="img fluid csharp-icon" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
            <img class="img fluid post-icon2" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
          </div>
          
        </div>
        <div class="col-6">
          <div class="me-4 mb-5">
            <img class="img-fluid keepr-img" src="https://figmage.com/images/KndD8m4gDG7hjt1xgq5lo.jpg" alt="Keepr">
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
          <img class="img-fluid allspice-img" src="https://codeworks.blob.core.windows.net/public/assets/img/projects/AllSpicePoster.jpg" alt="Keepr">
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
<section id="#contact">
  <div class="background-img2">
    <div class="row">
      <!-- TODO set up formsubmit path to send emails to me -->
      <div class="col-8 m-auto">
        <div class="form card p-4 ms-5 mt-5 mb-5">
          <h3 class="fs-1 text-black text-center mb-4">Get In Touch</h3>
          <form action="https://formsubmit.co/7821106b1e4ce3ae17cfdca1e845b808" method="POST">
            <div class="row">
              <div class="col form-floating mb-3">
                <input type="text" class="form-control" id="firstName" required placeholder="First Name" aria-label="First name">
                <label class="ms-2" for="firstName">First Name</label>
              </div>
              <div class="col form-floating mb-3">
                <input type="text" class="form-control" id="lastName" required placeholder="Last Name" aria-label="Last name">
                <label class="ms-2" for="lastName">Last Name</label>
              </div>
            </div>
            <div class="col form-floating mb-3">
              <input type="email" class="form-control" id="emailaddress" required placeholder="name@example.com">
              <label for="emailaddress">Email address</label>
            </div>
            <div class="mb-3">
              <!-- <label for="exampleFormControlTextarea1" class="form-label">Message</label> -->
              <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Message" rows="5" required></textarea>
            </div>

              <button class="btn btn-primary">Send</button>
          </form>
        </div>
      </div>

      <div class="d-flex justify-content-center mb-2">
        <a href="https://www.linkedin.com/in/andrewallison2/"><i class="mdi mdi-linkedin fs-1 linked-in selectable mx-2" title="View LinkedIn" ></i></a>
        <a href="https://www.linkedin.com/in/andrewallison2/"><i class="mdi mdi-github fs-1 github selectable mx-2" title="View Github" ></i></a>
        <a class="d-flex align-items-center" href="https://drive.google.com/file/d/1my5l6ozTgBCeG6Wc3yY_qn6lF5izV3Ee/view?usp=drive_link">
          <i class="mdi mdi-file fs-1 resume selectable mx-2" title="View/Download Resume"></i>
        </a>
        
      </div>

  </div>
  </div>
</section>

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
  background-image: url('https://static.vecteezy.com/system/resources/previews/002/821/966/original/abstract-triangular-geometric-background-free-vector.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh;
}
.background-img2{
  background-image: url('https://static.vecteezy.com/system/resources/previews/002/821/966/original/abstract-triangular-geometric-background-free-vector.jpg');
  background-size: cover;
  background-repeat: no-repeat;

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

.avatar {
  height: 20em;
  width: 20em;
  border-radius: 50%;
  object-fit: cover;
}

.linked-in{
  color: black;
}
.github{
  color: black;
}
.resume{
  color: black;
}

.form {
  width: 90%;
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




</style>
