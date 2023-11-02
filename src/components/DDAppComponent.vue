<template>

      <div class="row mt-3" id="devs&dragons">
      <div class="col-md-6 col-12 order-md-2 order-2">
        <div class="mb-5 img-container">
          <a href="https://github.com/AndrewAllison2/devs_and_dragons">
            <img class="img-fluid" src='../assets/img/DDScreenshot.png' alt="Devs & Dragons" title="View Github Repo">
          </a>
        </div>
      </div>

      <div class="col-md-6 col-12 order-md-1 order-1">
        <div class="mb-3 text-white dd-content">
          <h3 class="text-center mb-3">Devs & Dragons</h3>
          <p class="mb-4">A Dungeons & Dragons campaign management application built with a Vue.Js front
          end and an Express/NodeJs back end that allows players to stay connected and coordinate their games.
          </p>

          <p class="mb-4">This application was built by a team of five developers utilizing Scrum and Agile practices to coordinate our organization and communication throughout the build process.</p>

          <p class="mb-4">In addition to using MongoDB to store user data, this application also implements the D&D API to quickly and seamlessly provide
          users with information on the vast number of items within the game</p>
        </div>


        <div class="sm-h-line"></div>

        <div class="d-flex justify-content-between align-items-center dd-icon-section">
          <img class="img fluid vue-icon" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
          <img class="img fluid node-icon" src="https://static-00.iconduck.com/assets.00/node-js-icon-454x512-nztofx17.png" alt="NodeJs" title="NodeJS/Express">
          <img class="img fluid mongo-icon" src="https://icons-for-free.com/iconfiles/png/512/MongoDB-1329545826074381322.png" alt="MongoDB" title="MongoDB">
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
.img-container{
  margin-left: 1.5rem;
}
.dd-content{
  margin-right: 1.5rem;
}
.sm-h-line {
  height: 1px;
  background: white;
  width: 100%;
}
.dd-icon-section{
  margin-top: 1rem;
  padding-left: 1rem;
  padding-right: 1rem;
}
.vue-icon {
  height: 8em;
}
.node-icon {
  height: 7em;
}
.mongo-icon{
  height: 7em;
}
.post-icon{
  height: 6.7em
}
@media screen and (max-width: 769px){
  .img-container{
    margin-right: 1.5rem;
  }
  .dd-content{
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .vue-icon{
    height: 4em;
  }
  .node-icon{
    height: 4em;
  }
  .mongo-icon{
    height: 4em;
  }
  .post-icon{
    height: 4em;
  }
}

</style>