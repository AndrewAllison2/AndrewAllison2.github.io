<template>
  <div class="container-fluid bg-black">


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
    <div class="row mt-3">
      <div class="col-6">
        <div class="ms-4 mb-5">
          <img class="img-fluid" src="../assets/img/Screenshot (2).png" alt="Devs & Dragons">
        </div>
      </div>

      <div class="col-6">
        <div class="me-4 mb-5 text-center text-white">
          <h3>Devs & Dragons</h3>
          <p>Devs & Dragons is a DnD campaign management application designed to create seamless coordination between players. This application was built over the course of two weeks by a team of five developers. Our build process included the design and utilization of our own Figma mocks, data UML, and Trello board, and heavy coordination and collaboration across the back and front end.  </p>

          <p>We observed Agile and Scrum practices throughout the project. Our coordination allowed us to minimize errors and conflicts, and maximize our efficiency, allowing us to complete this large and complex application within the time frame.</p>
        </div>

        <div class="sm-h-line"></div>

        <div class="d-flex justify-content-between align-items-center mx-2">
          <img class="img-fluid html-icon" src="https://cdn3d.iconscout.com/3d/free/thumb/free-html-5728485-4781249.png" alt="HTML" title="HTML5">
          <img class="img fluid css-icon" src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" alt="CSS" title="CSS3">
          <img class="img fluid js-icon" src="https://static.vecteezy.com/system/resources/previews/027/127/463/original/javascript-logo-javascript-icon-transparent-free-png.png" alt="JavaScript" title="JavaScript">
          <img class="img fluid vue-icon" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid node-icon" src="https://static-00.iconduck.com/assets.00/node-js-icon-454x512-nztofx17.png" alt="NodeJs" title="NodeJS/Express">
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

.h-line {
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

.css-icon {
  height: 8em;
}

.js-icon {
  height: 8em;
}

.vue-icon {
  height: 8em;
}

.node-icon {
  height: 7em;
}



</style>
