<template>

  <section id="contact" class="contact">
  <div class="background-img2">
    <div class="row">
      <!-- TODO set up formsubmit path to send emails to me -->
      <div class="col-8 m-auto">
        <div class="form card p-4 ms-5 mt-5 mb-5">
          <h3 class="fs-1 text-black text-center mb-4">Get In Touch</h3>
          <form action="https://formsubmit.co/7821106b1e4ce3ae17cfdca1e845b808" method="POST">
            <div class="row">
              <div class="col form-floating mb-3">
                <input type="text" class="form-control" id="firstName" required placeholder="First Name" aria-label="First name" name="first-name">
                <label class="ms-2" for="firstName">First Name</label>
              </div>
              <div class="col form-floating mb-3">
                <input type="text" class="form-control" id="lastName" required placeholder="Last Name" aria-label="Last name" name="last-name">
                <label class="ms-2" for="lastName">Last Name</label>
              </div>
            </div>
            <div class="row">
            <div class="col form-floating mb-3">
              <input type="email" class="form-control" id="emailaddress" required placeholder="name@example.com" name="email">
              <label class="ms-2" for="emailaddress">Email address</label>
            </div>
              <div class="col form-floating mb-3">
                <input class="form-control" type="tel" id="phone" name="phone" placeholder="Enter your phone number" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" title="XXX-XXX-XXXX">
                <label class="ms-2" for="phone">Phone Number</label>
                
              </div>
            </div>
            <!-- <div class="col form-floating mb-3">
              <input type="email" class="form-control" id="emailaddress" required placeholder="name@example.com">
              <label for="emailaddress">Email address</label>
            </div> -->
            <div class="mb-3">
              <!-- <label for="exampleFormControlTextarea1" class="form-label">Message</label> -->
              <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Your message" rows="5" required name="message" maxlength="2500"></textarea>
            </div>

              <button class="btn btn-primary">Send</button>
          </form>
        </div>
      </div>

      <div class="d-flex justify-content-center mb-2">
        <a href="https://www.linkedin.com/in/andrewallison2/"><i class="mdi mdi-linkedin fs-1 linked-in selectable mx-2" title="View LinkedIn" ></i></a>
        <a href="https://github.com/AndrewAllison2"><i class="mdi mdi-github fs-1 github selectable mx-2" title="View Github" ></i></a>
        <a class="d-flex align-items-center" href="https://drive.google.com/file/d/1my5l6ozTgBCeG6Wc3yY_qn6lF5izV3Ee/view?usp=drive_link">
          <i class="mdi mdi-file fs-1 resume selectable mx-2" title="View/Download Resume"></i>
        </a>
        
      </div>

  </div>
  </div>
</section>

</template>


<script>
export default {
  setup(){
    return {}
  }
}
</script>


<style lang="scss" scoped>
.background-img2{
  background-image: url('https://static.vecteezy.com/system/resources/previews/002/821/966/original/abstract-triangular-geometric-background-free-vector.jpg');
  background-size: cover;
  background-repeat: no-repeat;
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
</style>