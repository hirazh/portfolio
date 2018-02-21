<template>
    <section id="contacts" class="contact">
        <div class="columns social-columns">
            <div class="column is-4">
                <a href="mailto:mhmdhiras@gmail.com"><i class="far fa-envelope"></i></a>  
            </div>
            <div class="column is-4">
                <a href="https://twitter.com/hirazhira"><i class="fab fa-twitter"></i></a>
            </div>
            <div class="column is-4">
                <a href="https://www.instagram.com/hirazz_m/"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  
}
</script>

<style>
.contact {
    margin-bottom: 12%;
}

.social-columns {
    margin-top: 10%;
    margin-bottom: 10%;
}

.is-4 {
    font-size: 5em;
}

.is-4 a {
    color: rgb(100, 100, 100);
    border-bottom: 3px solid rgb(100, 100, 100);
}

.is-4:hover a {
    border-bottom: 3px solid #4756ca;
    transition: linear 50ms;
}

@media only screen and (max-width: 760px) {
  .is-4 {
      font-size: 3em;
      padding: 5%;
  }
}
</style>
