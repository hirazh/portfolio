<template>
    <div id="aboutMe">
        <h1>About Me</h1>
        <div class="columns">
            <div class="column is-6">
                <img src="../../assets/logo.png">
            </div>
            <div class="column is-6">
                <p>{{aboutMe}}</p>
            </div>
        </div>
    </div>  
</template>

<script>
export default {
  data () {
      return {
          aboutMe: 'Hi, Im Hiras I am a webdeveloper Just trying to build cool websites'
      }
  }
}
</script>

<style>

</style>
