<template>
  <section class="hero is-primary is-medium">
    <navbar />
    <div class="hero-body">
      <div class="container">
        <div class="columns">
          <div class="column is-6 is-info" style="background: #7F00FF">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium deserunt distinctio
            dolore earum fuga maxime modi. Accusantium, molestiae quam? Aliquid expedita Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci aliquam architecto consequatur excepturi expedita ipsum laborum odio omnis quibusdam temporibus. Commodi deserunt doloremque facilis, hic itaque numquam praesentium quibusdam vero. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad animi cupiditate deleniti eligendi exercitationem facilis laborum mollitia, nesciunt ratione reiciendis repellendus temporibus veniam, Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur cum cupiditate doloremque ducimus, eligendi iusto magnam nobis numquam optio possimus, quibusdam repudiandae rerum! Ab ea iusto molestias quisquam repellendus tenetur! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus aliquid distinctio dolores, eveniet impedit laborum nisi optio porro provident quas, qui, quos tenetur voluptatem. Atque dignissimos laborum maiores officiis quod! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet eligendi facere sequi. Aliquid facilis ipsam laudantium rem repudiandae. Ea, ipsum velit? A accusamus blanditiis dicta est illo, necessitatibus suscipit tempore?voluptatem? Ducimus incidunt minus numquam officia voluptas?incidunt ipsa numquam vel? Id necessitatibus rem saepe sint!</div>
          <div class="column is-6 " style="background: #3B8070">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A culpa deleniti deserunt error iste maxime nisi ratione rerum tempora tempore. A adipisci aspernatur consequatur facere ipsum natus numquam quia tempora.</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    import AppLogo from '~/components/AppLogo.vue'
    import Banner from "../components/Banner";
    import Navbar from "../components/NavBar";

    export default {
        components: {
            Navbar,
            Banner,
            AppLogo
        }
    }
</script>

<style>
  .container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }
</style>

