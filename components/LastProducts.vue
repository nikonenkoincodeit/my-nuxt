<template>
  <div class="container">
    <div class="last-products">
      <h2>Last added products</h2>

      <section class="products">
        <no-ssr>
          <splide>
            <splide-slide>
              <img src="../assets/images/11.jpg" />
            </splide-slide>
            <splide-slide>
              <img src="../assets/images/12.jpg" />
            </splide-slide>
            <splide-slide>
              <img src="../assets/images/13.jpg" />
            </splide-slide>
          </splide>
        </no-ssr>
        <!-- <article>
          <img src="../assets/images/11.jpg" alt="" />
          <h3>Lorem ipsum dolor</h3>
          <h4>$990.00</h4>
          <a href="cart.html" class="btn-add">Add to cart</a>
        </article>
        <article>
          <img src="../assets/images/12.jpg" alt="" />
          <h3>cupidatat non proident</h3>
          <h4>$1 200.00</h4>
          <a href="cart.html" class="btn-add">Add to cart</a>
        </article>
        <article>
          <img src="../assets/images/13.jpg" alt="" />
          <h3>Duis aute irure</h3>
          <h4>$2 650.00</h4>
          <a href="cart.html" class="btn-add">Add to cart</a>
        </article>
        <article>
          <img src="../assets/images/14.jpg" alt="" />
          <h3>magna aliqua</h3>
          <h4>$3 500.00</h4>
          <a href="cart.html" class="btn-add">Add to cart</a>
        </article> -->
      </section>
    </div>
  </div>
</template>

<script>
import NoSSR from "vue-no-ssr";
export default {
  name: "LastProducts",
  components: {
    "no-ssr": NoSSR
  }
};
</script>

<style lang="scss">
@import "~/assets/css/splide-core.min.scss";
@import "~/assets/css/splide.min.scss";
</style>
