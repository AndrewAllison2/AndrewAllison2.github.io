<template>
  <nav class="navbar navbar-expand-lg navbar-dark nav-background px-3 fixed-top">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
      aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">
        <li>
          <a class="btn text-success selectable text-uppercase me-5 px-5" href="#home" id="home">Home</a>
          <a class="btn text-success selectable text-uppercase mx-5 px-5" href="#about" id="#about">About</a>
          <a class="btn text-success selectable text-uppercase mx-5 px-5" href="#applications">Applications</a>
          <a class="btn text-success selectable text-uppercase mx-5 ps-5" href="#contact">Contact</a>
            
          
        </li>
      </ul>
      <!-- LOGIN COMPONENT HERE -->
      <!-- <Login /> -->
    </div>
  </nav>
</template>

<script>
// import Login from './Login.vue';
export default {
  setup() {
    return {}
  },
  // components: { Login }
}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

.nav-background {
background-color: black;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
</style>
