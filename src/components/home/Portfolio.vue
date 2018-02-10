<template>
    <section class="section portfolio" id="portfolio">
        <h1>Portfolio</h1>
        <div class="tile is-ancestor">
          <div class="portfolio-sites" v-for="(item, index) in testdata" :key='index'>
            <h3>{{item.name}}</h3>
            <img :src="item.image">
          </div>
        </div>
    </section>  
</template>

<script>
export default {
    data () {
        return {
            testdata: [
                { name: 'Project1', image:'https://www.extremetech.com/wp-content/uploads/2018/02/Tesla-Model-3.jpg'},
                { name: 'Project2', image:'https://cleantechnica.com/files/2017/01/Tesla-Model-3-red.png'}
            ]
        }
    }
}
</script>

<style>
h1 {
    text-align: center;
}
</style>
