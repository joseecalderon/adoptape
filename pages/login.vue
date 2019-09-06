<template>
  <section class="hero is-fullheight">
    <!-- Hero head: will stick at the top -->
    <div class="hero-head">
      <navbar/>
    </div>

    <!-- Hero content: will be in the middle -->
    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="columns">
          <div class="column is-5 is-offset-1 landing-caption">
            <h1 class="title is-1 is-bold is-spaced">adoptape.</h1>
            <div class="sub-title is-5 is-muted">Un perro es el único animal que te ama más a ti que a sí mismo
              <p><a class="button cta rounded primary-btn raised">Descargar</a></p>
            </div>
          </div>
          <div class="column is-5 is-offset-1">
            <img class="image-hero" src="../assets/img/puppy.jpg">
          </div>
        </div>
      </div>
    </div>

    <!-- Hero footer: will stick at the bottom -->
    <div class="hero-foot">
      <nav class="tabs is-boxed is-fullwidth">
        <div class="container">
          <ul>
            <li class="is-active"><a>Overview</a></li>
            <li><a>Modifiers</a></li>
            <li><a>Grid</a></li>
            <li><a>Elements</a></li>
            <li><a>Components</a></li>
            <li><a>Layout</a></li>
          </ul>
        </div>
      </nav>
    </div>
  </section>
</template>

<script>
    import Navbar from "../components/NavBar";

    export default {
        name: "login",
        components: {Navbar}
    }
</script>

<style scoped>

</style>
