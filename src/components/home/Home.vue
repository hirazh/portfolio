<template>
 <div id="home">
     <section class="section home-section">
         <div class="landing-text">
             <h1 class="title is-1">Design</h1>
             <h1 class="title is-1">Code</h1>
         </div>
         <i class="fas fa-angle-down fa-5x"></i>
     </section>
 </div>
</template>


<script>
export default {
  data () {
      return {
          test: 'Home sweet home'
      }
  }
}
</script>

<style>

.home-section {
    height: 90vh;
    text-align: center;
}

.landing-text {
    text-align: center;
}
</style>
