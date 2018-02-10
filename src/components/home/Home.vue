<template>
    <section class="section home-section" id="home">
         <div class="landing-text">
            <h1>Design</h1>
            <h1>Code</h1>
             <!--
             <i class="fas fa-angle-down fa-5x"></i>
             -->
            <i class="fas fa-angle-double-down fa-2x"></i>
         </div>
         
    </section>
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
    background-color: #4756ca;
    color: #fcfcfc;
    /* vertically align the landing-text div*/
    display: flex;
    align-items: center;
    justify-content: center;
}

.landing-text h1 {
    font-family: 'Anton', sans-serif;
    font-size: 6em;
    font-weight: bolder;
    letter-spacing: 2px;
    padding: 5%;
}

.fa-2x {
    margin-top: 6%;
}
</style>
