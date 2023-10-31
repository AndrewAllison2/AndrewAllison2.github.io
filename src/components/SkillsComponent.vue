<template>

  <div class="bg-black">
        <div class="row">
          <h1 class="text-center mt-3" style='color:#f7a51b'>My Skills</h1>
          <div class="col-12 d-flex align-content-center">
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

</template>


<script>
export default {
  setup(){
    return {}
  }
}
</script>


<style lang="scss" scoped>
.skills-icons{
  overflow-x: hidden;
  align-items: center;
}
</style>