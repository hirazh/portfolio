<template>
    <section class="section portfolio" id="portfolio">
        <h1 class="title is-3">Portfolio</h1>
        <div class="card-wrapper">
            <a v-bind:href="project.url" v-for="(project, index) in myProjects" :key="index">
                <div class="card">
                    <div class="card-image">
                        <figure class="image is-3by2">
                            <img v-bind:src="project.image">
                        </figure>
                    </div>
                    <div class="card-content">
                        <h2 class="title is-5">{{project.name}}</h2>
                    </div> 
                </div>
            </a>
        </div>
    </section>  
</template>

<script>
export default {
  data() {
    return {
      myProjects: [
        {
          name: "Elon Musk",
          image: require("../../assets/elon-image.png"),
          url: "https://codepen.io/hiras/full/awOoxe/"
        },
        {
          name: "Weather App",
          image: require("../../assets/weatherApp.png"),
          url: "https://codepen.io/hiras/full/rpgGeV/"
        },
        {
          name: "CSS Grid",
          image: require("../../assets/img-gallery.png"),
          url: ""
        },
        {
          name: "Quote Generator",
          image: require("../../assets/quote-generator.png"),
          url: "https://codepen.io/hiras/full/mBbQQx/"
        }
      ]
    };
  }
};
</script>

<style>
.portfolio h1 {
  text-align: center;
  font-family: "Lato", sans-serif;
  margin-top: 5%;
  color: rgb(100, 100, 100);
}
.card-wrapper {
    display: flex;
    flex-flow: row wrap;
    justify-content: space-around;
    margin-left: 5%;
    margin-right: 5%;
}

.card {
  width: 300px;
  margin-top: 50px;
  margin-bottom: 50px;
}

.card:hover {
    border: solid 5px;
    border-color: #0fc9e7;
    transition: linear 100ms;
}
.title {
    text-align: center;
    font-family: "Lato", sans-serif;
    letter-spacing: 1px;
    color: rgb(100, 100, 100);   
}
</style>
