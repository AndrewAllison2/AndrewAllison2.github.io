<template>

      <div class="row mt-3" id="keepr">
          
        <div class="col-md-6 col-12">
          <div class="mb-3 text-white keepr-content">
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

        </div>
        
        <div class="sm-h-line mt-4"></div>
        
        <div class="d-flex justify-content-between align-items-center mt-4 keepr-icon-section">
            <img class="img fluid vue-icon2" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/367_Vuejs_logo-512.png" alt="VueJs" title="VueJs">
            <img class="img fluid mysql-icon" src="https://cdn4.iconfinder.com/data/icons/logos-3/181/MySQL-512.png" alt="MySQL" title="MySQL">
            <img class="img fluid csharp-icon" src="https://www.freeiconspng.com/uploads/c-logo-icon-18.png" alt="C#" title="C#">
            <img class="img fluid post-icon" src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" title="Postman">
          </div>
          
        </div>
        <div class="col-md-6 col-12">
          <div class="me-4 mb-5 img-container">
            <a href="https://github.com/AndrewAllison2/keepr">
              <img class="img-fluid keepr-img" src="https://figmage.com/images/KndD8m4gDG7hjt1xgq5lo.jpg" alt="Keepr" title="View Github Repo">
            </a>
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
.keepr-content{
  margin-left: 1.5rem;
}
.sm-h-line {
  height: 1px;
  background: white;
  width: 100%;
}

.keepr-img {
  height: 25em;
  width: 100%;
  object-fit: cover;
}
.vue-icon2 {
  height: 8em;
  margin-left: 0.5rem;
}
.mysql-icon {
  height: 8em;
}
.csharp-icon {
  height: 7em;
}
.post-icon{
  height: 6.7em
}
@media screen and (max-width: 769px){
  .keepr-content{
    margin-right: 1.5rem;
  }
  .keepr-icon-section{
    padding: 1rem;
  }
  .keepr-img{
    height: auto;
    margin-left: 0.7rem;
    margin-top: 1rem;
  }
  .vue-icon2{
    height: 4em;
    margin-left: 0;
  }
  .mysql-icon{
    height: 4em;
  }
  .csharp-icon{
    height: 4em;
  }
  .post-icon{
    height: 4em;
  }
}
</style>