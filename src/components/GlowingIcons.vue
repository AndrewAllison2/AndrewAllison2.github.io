<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12">
        <div class="text-center align-content-center">
          <a class="mdi mdi-email fs-2 my-3" id="email" title="E-Mail"> <span class="fs-5"> : andrewallison5211@gmail.com</span></a>
          <a class="mdi mdi-phone fs-2 my-3" id="phone" title="Phone"> <span class="fs-4"> : 208-869-5211</span></a>
          <a class="mdi mdi-github fs-2 my-3" id="github" title="Github" href="https://github.com/AndrewAllison2"> <span class="fs-4"> : Github</span></a>
          <a class="mdi mdi-linkedin fs-2 my-3" id="linkedin" title="LinkedIn" href="https://www.linkedin.com/in/andrew-allison-91a213288/"> <span class="fs-4"> : LinkedIn</span></a>
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

#github,
#linkedin,
#email,
#phone,
#twitter {
  display: block;
  width: 12em;
  background-color: #18191f;
  color: #fff;
  box-shadow: 2px 2px 2px #00000080, 
              10px 1px 12px #00000080,
              2px 2px 10px #00000080,
              2px 2px 3px #00000080,
              inset 2px 2px 10px #00000080,
              inset 2px 2px 10px #00000080,
              inset 2px 2px 10px #00000080,
              inset 2px 2px 10px #00000080;
  border: 2px solid gray;
  border-radius: 29px;
  padding: 11px 19px;
  margin: 0 8px;
  animation: animate 5s linear infinite;
  text-shadow: 0 0 50px #0072ff, 
               0 0 100px #0072ff,
               0 0 150px #0072ff,
               0 0 200px #0072ff;
  
}
#github{
  animation-delay: 0.8s;
}
#linkedin {
  animation-delay: 1.6s;
}
#email{
  animation-delay: 01.2s;
}
#phone{
  animation-delay: 0.1s;
}
#twitter{
  animation-delay: 2.0s;
}
@keyframes animate {
  from {
    filter: hue-rotate(0deg);
  }
  to {
    filter: hue-rotate(360deg);
  }
}

</style>