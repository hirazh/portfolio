<template>
  <div id="app">
    <header>
      <div class="navbar is-fixed-top">
        <div class="navbar-end">
          <a class="navbar-item" href="#app">Home</a>
          <a class="navbar-item" href="#portfolio">Portfolio</a>
          <a class="navbar-item" href="#aboutMe">About Me</a>
          <a class="navbar-item" href="#contacts">Contacts</a>
        </div>
      </div>
    </header>

    <Home></Home>
    <Portfolio></Portfolio>
    <AboutMe></AboutMe>
    <Contacts></Contacts>

    <footer>
      <h3>Hiras</h3>
    </footer>

  </div>
</template>

<script>
import Home from './components/home/Home.vue'
import Portfolio from './components/home/Portfolio.vue'
import AboutMe from './components/home/AboutMe.vue'
import Contacts from './components/home/Contacts.vue'

export default {
  name: 'App',
  components: {
    Home,
    Portfolio,
    AboutMe,
    Contacts
  }
}
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
  font-family: 'Lato', sans-serif;
}

a {
  font-size: 1.2em;
  letter-spacing: 1px;
}
.navbar-end {
  margin-right: 5%;
}

footer {
  padding: 30px;
  text-align: center;
}

@media only screen and (max-width: 1024px) {
  .navbar-end {
    display: none;
  } 
}
</style>
