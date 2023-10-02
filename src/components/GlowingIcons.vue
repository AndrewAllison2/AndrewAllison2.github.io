<template>

  <div>
          <a class="mdi mdi-github fs-5" id="github" title="Github" href="https://github.com/AndrewAllison2"></a>
          <a class="mdi mdi-linkedin fs-5" id="linkedin" title="LinkedIn" href="https://www.linkedin.com/in/andrew-allison-91a213288/"></a>
          <!-- <a class="mdi mdi-email fs-5" id="email" title="E-Mail" href="https://mail.google.com/mail/u/0/#inbox?compose=GTvVlcSBnqHwtwrPxWvdnzlFBHmqjthwCzJgtdGxTglFWvndKqFzhLCwBprgmPTXsDrGNhctjRTsr"></a>-->
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
#instagram,
#twitter {
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
#instagram{
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