<template>
  <div id="body">
    <Slider />
    <LastProducts />
    <!-- <div class="container">
      <div class="last-products">
        <h2>Last added products</h2>
        <section class="products">
          <article>
            <img src="../assets/images/1.jpg" alt="" />
            <h3>Excepteur sint occaecat</h3>
            <h4>$1 850.00</h4>
            <a href="cart.html" class="btn-add">Add to cart</a>
          </article>
          <article>
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
          </article>
        </section>
      </div> -->
    <QuickLinks />
    <!-- / container -->
  </div>
  <!-- / body -->
</template>
<script>
import Slider from "../components/Slider";
import QuickLinks from "../components/QuickLinks";
import LastProducts from "../components/LastProducts";

export default {
  name: "PageIndex",
  components: {
    LastProducts,
    QuickLinks,
    Slider
  }
};
</script>
