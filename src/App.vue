<template>
  <div id="app">
    <header>
      <div class="navbar">
        <div class="navbar-end">
          <a class="navbar-item">Home</a>
          <a class="navbar-item">Portfolio</a>
          <a class="navbar-item">About Me</a>
          <a class="navbar-item">Contacts</a>
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
}

footer {
  padding: 30px;
  text-align: center;
}
</style>
