<template>
  <div id="app">
    <header>
      <div class="navbar is-fixed-top">
        <div class="navbar-end">
          <a class="navbar-item" v-scroll-to="'#app'">Home</a>
          <a class="navbar-item" v-scroll-to="'#portfolio'">Portfolio</a>
          <a class="navbar-item" v-scroll-to="'#aboutMe'">About Me</a>
          <a class="navbar-item" v-scroll-to="'#contacts'">Contacts</a>
        </div>
      </div>
    </header>

    <Home></Home>
    <Portfolio></Portfolio>
    <AboutMe></AboutMe>
    <Contacts></Contacts>

    <footer id="ftr">
      <h3>HIRAZ</h3><br>
      Github: <a href="https://github.com/hirazh">hirazh</a><br>
      CodePen: <a href="https://codepen.io/hiras/">@hiras</a><br><br>
      <a href="https://twitter.com/hirazhira"><i class="fab fa-twitter"></i></a>
      <a href="https://www.instagram.com/hirazz_m/"><i class="fab fa-instagram"></i></a>
    </footer>

  </div>
</template>

<script>
import Home from "./components/home/Home.vue";
import Portfolio from "./components/home/Portfolio.vue";
import AboutMe from "./components/home/AboutMe.vue";
import Contacts from "./components/home/Contacts.vue";

export default {
  name: "App",
  components: {
    Home,
    Portfolio,
    AboutMe,
    Contacts
  }
};
</script>

<style>
header {
  height: 10vh;
  background-color: #4756ca;
}

.navbar {
  background-color: #4756ca;
}

.navbar-item {
  color: #fcfcfc;
}

.navbar-item a {
  font-family: "Lato", sans-serif;
}

a {
  font-size: 1.2em;
  letter-spacing: 1px;
}
.navbar-end {
  margin-right: 5%;
}

footer {
  padding: 40px;
  text-align: center;
  font-family: "Anton", sans-serif;
  background-color: #4756ca;
  color: #fcfcfc;
}
footer a {
  color: #fcfcfc;
}

@media only screen and (max-width: 1024px) {
  .navbar-end {
    display: none;
  }

  header {
    border-bottom: 1px #fcfcfc solid;
  }
}



</style>
