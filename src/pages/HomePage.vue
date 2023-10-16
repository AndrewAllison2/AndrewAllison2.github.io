<template>
  <div class="container-fluid bg-black">

    <div class="row">
      <div class="mt-4 text-end">
        <!-- <GlowingIcons /> -->
      </div>
    </div>

    <div class="row mb-5">
      <div class="col-10 m-auto mt-5 me-5">
        <div class="mt-5 ms-5 text-white">
          <h1 class="fs-5">Hi, I'm Andrew</h1>
          <h1 class="fs-5">A full stack <span class="fs-1 text-warning">Software Developer</span></h1>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-10 m-auto my-5">
        <div class="h-line"></div>
      </div>
    </div>

    <div class="row">
      <div class="col-8 m-auto my-5">
        <h2 class="fs-1 text-white text-center">Applications</h2>

        <div class="d-flex justify-content-between text-warning mt-5">
          <h3 class="selectable" title="Devs & Dragons">Devs & Dragons</h3>
          <h3 class="selectable" title="Keepr">Keepr</h3>
          <h3 class="selectable" title="AllSpice">AllSpice</h3>
        </div>
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
        <div class="me-4 mb-3 text-center text-white">
          <h3>Devs & Dragons</h3>
          <p>Devs & Dragons is a DnD campaign management application designed to create seamless coordination between players. This application was built over the course of two weeks by a team of five developers. Our build process included the design and utilization of our own Figma mocks, data UML, and Trello board, and heavy coordination and collaboration across the back and front end.  </p>

          <p>We observed Agile and Scrum practices throughout the project. Our coordination allowed us to minimize errors and conflicts, and maximize our efficiency, allowing us to complete this large and complex application within the time frame.</p>
        </div>

        <div class="sm-h-line"></div>

        <div class="d-flex justify-content-between align-items-center mx-2 mt-4">
          <img class="img-fluid html-icon" src="https://cdn3d.iconscout.com/3d/free/thumb/free-html-5728485-4781249.png" alt="HTML" title="HTML5">
          <img class="img fluid css-icon" src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" alt="CSS" title="CSS3">
          <img class="img fluid js-icon" src="https://static.vecteezy.com/system/resources/previews/027/127/463/original/javascript-logo-javascript-icon-transparent-free-png.png" alt="JavaScript" title="JavaScript">
          <img class="img fluid vue-icon" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid node-icon" src="https://static-00.iconduck.com/assets.00/node-js-icon-454x512-nztofx17.png" alt="NodeJs" title="NodeJS/Express">
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
        <div class="ms-4 mb-5">
          <img class="img-fluid keepr-img" src="https://figmage.com/images/KndD8m4gDG7hjt1xgq5lo.jpg" alt="Keepr">
        </div>
      </div>

      <div class="col-6">
        <div class="me-4 mb-3 text-center text-white">
          <h3>Keepr</h3>
          <p>A full-stack web application similar to Pintrest I built over the course of a week. Users are able to upload
            and share photos, save them in public and private vaults, and display their favorites on their profile page.
            This application utilizes an auth0 authenticator, requiring users to create an account and login to upload
            and save photos. Users can still browse public photos and vaults without logging in.
          </p>

          <p>This application was built with a Vue.Js front end and a .Net/MySQL back end, and included API testing
            with Postman, mobile optimization, and accessibility/best practices testing with Lighthouse.</p>


        </div>

        <div class="sm-h-line mt-4"></div>

        <div class="d-flex justify-content-between align-items-center mx-2 mt-4">
          <img class="img-fluid html-icon2" src="https://cdn3d.iconscout.com/3d/free/thumb/free-html-5728485-4781249.png" alt="HTML" title="HTML5">
          <img class="img fluid css-icon2" src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" alt="CSS" title="CSS3">
          <img class="img fluid js-icon2" src="https://static.vecteezy.com/system/resources/previews/027/127/463/original/javascript-logo-javascript-icon-transparent-free-png.png" alt="JavaScript" title="JavaScript">
          <img class="img fluid vue-icon2" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid mysql-icon" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
          <img class="img fluid csharp-icon" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
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
        <div class="me-4 mb-3 text-center text-white">
          <h3>AllSpice</h3>
          <p>A full stack recipe management web application I built over the course of a week. Similar to recipe apps
            from Home Chef or Dinnerly, users are able to create recipes once logged in. They can add ingredients and
            preperation instructions, save their favorite recipes, and filter recipes by type.
            User authentication is handled by auth0, requiring an account to create or save any recipes or ingredients.
            Recipes can still be viewed without an account.
          </p>

          <p>This application was built using a Vue.Js front end and a .Net/MySQL back end, and the API was tested
            with Postman.</p>
        </div>

        <div class="sm-h-line mt-4"></div>

        <div class="d-flex justify-content-between align-items-center mx-2 mt-4">
          <img class="img-fluid html-icon2" src="https://cdn3d.iconscout.com/3d/free/thumb/free-html-5728485-4781249.png" alt="HTML" title="HTML5">
          <img class="img fluid css-icon2" src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" alt="CSS" title="CSS3">
          <img class="img fluid js-icon2" src="https://static.vecteezy.com/system/resources/previews/027/127/463/original/javascript-logo-javascript-icon-transparent-free-png.png" alt="JavaScript" title="JavaScript">
          <img class="img fluid vue-icon2" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid mysql-icon" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
          <img class="img fluid csharp-icon" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
        </div>

        </div>
      </div>

        <div class="row">
          <div class="col-12 m-auto my-5">
            <div class="full-h-line"></div>
          </div>
        </div>

    <!-- SECTION ABOUT ME -->

    <div class="row">
      <div class="col-5 text-center">
        <img class="img-fluid avatar" src="../assets/img/Professional Photo.jpg" alt="Andrew Allison">
      </div>

      <div class="col-5 text-center">
        <div class="text-white">
          <h3 class="fs-3">About Me</h3>
          <p class="mt-3">Hi. I'm a software developer based in Boise, Idaho.</p>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-12 m-auto my-5">
        <div class="h-line"></div>
      </div>
    </div>

    <!-- SECTION FORM -->

    <div class="row">
      <!-- TODO set up formsubmit path to send emails to me -->
      <div class="col-6 m-auto">
        <div class="form card p-4 ms-5 mt-1 mb-5">
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

      <div class="col-6 text-white">
        <div>
          <h3 class="fs-1 text-center">Connect</h3>
          <div class="mt-3 icons">
            <GlowingIcons />
          </div>
        </div>
      </div>


    </div>

  </div>
</template>

<script>
import { ref } from "vue";



export default {

  
  setup() {
    const activeApp = ref('')


    
        return {};
    },

}
</script>

<style scoped lang="scss">

.h-line {
  height: 1px;
  width: 100%;
  background: white;
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

.vue-icon {
  height: 8em;
}
.vue-icon2 {
  height: 6em;
}

.node-icon {
  height: 7em;
}

.mysql-icon {
  height: 6em;
}

.csharp-icon {
  height: 6em;
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

.form {
  width: 90%;
}

// .icons {
//   position: relative;
//   left: 4em;
// }



</style>
