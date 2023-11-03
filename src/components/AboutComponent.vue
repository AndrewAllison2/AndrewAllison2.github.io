<template>

  <div class="background-sec">
        <div class="row">
        <div class="col-md-5 col-12 text-center avatar-container order-md-1 order-2">
          <img class="img-fluid avatar" src="../assets/img/Professional-Photo.jpg" alt="Andrew Allison">
        </div>
  
        <div class="col-md-5 col-12 about-container order-md-2 order-1">
          <div class="text-white about-content">
            <h2 class="mb-4" style='color:#f7a51b'>About Me</h2>
            <h5 class="mt-3 mb-3 font-italic">Hi, I'm Andrew!</h5>
            <p>I'm a passionate creator with a knack for design and problem solving. I enjoy designing and building intuitve UI's, as well as dealing with complex logic and data management. I thouroghly enjoy being challenged and working through problems to find creative solutions.</p>
            
            <p>Some of my hobbies include writing music, traveling to new places, and spending time outdoors with my wife and our golden retriever. I love learning new things and expanding my knoweldge in fields that I find interesting.</p>
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
.background-sec {
  background: rgb(25,96,98);
background: linear-gradient(90deg, rgba(25,96,98,1) 0%, rgba(7,53,69,1) 35%, rgba(25,96,98,1) 100%);
height: 75vh;
}
.about-container{
  margin-top: 3rem;
  margin-bottom: 3rem;
  padding-top: 3rem;
}
.avatar-container{
  padding-top: 3rem;
  margin-top: 3rem;
  margin-bottom: 3rem;
}

.avatar {
  height: 25em;
  width: 25em;
  border-radius: 50%;
  object-fit: cover;
}

@media screen and (max-width: 769px) {
  .background-sec{
    height: 100%;
  }
.avatar-container{
  padding-top: 1rem;
  margin-top: 1rem;
  margin-bottom: 3rem;
}
.about-container{
  margin-top: 1rem;
  padding-top: 1rem;
  margin-bottom: 1rem;
}
.avatar{
  height: 15em;
  width: 15em;
}
.about-content{
  padding-left: 1rem;
  padding-right: 1rem;
  margin-top: 1rem;
}
}
</style>