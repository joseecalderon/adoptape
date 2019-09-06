<template>
  <nav class="navbar is-fresh is-transparent no-shadow" role="navigation" aria-label="main navigation">
    <div class="container">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">
          <h1 class="logo">adoptape.</h1>
        </a>
        <div class="navbar-burger" @click="showNav = !showNav" :class="{ 'is-active': showNav }">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
      <div class="navbar-menu is-static" :class="{ 'is-active': showNav }">
        <div class="navbar-end ">
          <a class="navbar-item is-secondary" href="/about">
            Adopta
          </a>
          <a class="navbar-item  is-secondary" href="/path">
            Contacto
          </a>
          <a class="navbar-item is-secondary" href="/blog">
            Donativos
          </a>
          <a href="#" class="navbar-item is-secondary modal-trigger" data-modal="auth-modal">
            Mi Albergue
          </a>
          <a class="navbar-item"><span class="button signup-button rounded secondary-btn raised">Quiero Ayudar !</span>'
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
    export default {
        name: "navbar",
        data() {
            return {
                showNav: false
            };
        },
        computed: {},
        methods: {},
        created() {
        },
        mounted() {
        },

    }
</script>

<style scoped>

</style>
