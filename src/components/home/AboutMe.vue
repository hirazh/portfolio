<template>
    <section id="aboutMe" class="me"> 
        <div class="columns">
            <div class="column is-6 image-column">
                
            </div>
            <div class="column is-6 paragraph-column">
                <p>{{aboutMe}}</p>
            </div>
        </div>
    </section>  
</template>

<script>
export default {
  data () {
      return {
        aboutMe: 'Hi..., I am Hiraz I am a front-end webdeveloper Just trying to build cool websites'
      }
    }
}
</script>

<style>

.column {
    display: flex;
    align-items: center;
    justify-content: center;
}

.column p {
    font-family: 'Anton', sans-serif;
    letter-spacing: 1px;
    line-height: 150%;
    font-size: 1.8em;
    margin-left: 15%;
    margin-right: 15%;
    color: #fcfcfc;
}

.image-column {
    background: linear-gradient(
        rgba(15, 201, 231, 0.3),
        rgba(15, 201, 231, 0.3)),
        url('../../assets/propic-portfolio.jpeg');
    height: 100vh;
    background-size: cover;
    background-position: center center;
}

.paragraph-column {
    background-color: #0fc9e7;
}

@media only screen and (max-width: 760px) {
  .paragraph-column {
      padding: 20%;
    }

    .column p {
        font-size: 1.4em;
    }
}
</style>
