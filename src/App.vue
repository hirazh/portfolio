<template>
  <div id="app">
    <header>
      <div class="navbar">
        <div class="navbar-end">
          <a class="navbar-item">Home</a>
          <a class="navbar-item">Portfolio</a>
          <a class="navbar-item">Contacts</a>
        </div>
      </div>
    </header>
    <Home></Home>
    <Portfolio></Portfolio>
  </div>
</template>

<script>
import Home from './components/home/Home.vue'
import Portfolio from './components/home/Portfolio.vue'
export default {
  name: 'App',
  components: {
    Home,
    Portfolio
  }
}
</script>

<style>
header {
  height: 10vh;
}
</style>
