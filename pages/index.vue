<template>
  <div>
    <nav id="menu">
      <div class="container">
        <div class="trigger" />
        <ul>
          <li><a href="products.html">New collection</a></li>
          <li><a href="products.html">necklaces</a></li>
          <li><a href="products.html">earrings</a></li>
          <li><a href="products.html">Rings</a></li>
          <li><a href="products.html">Gift cards</a></li>
          <li><a href="products.html">Promotions</a></li>
        </ul>
      </div>
      <!-- / container -->
    </nav>
    <!-- / navigation -->
    <div id="slider">
      <ul>
        <li>
          <h3>Make your life better</h3>
          <h2>Genuine diamonds</h2>
          <a href="#" class="btn-more">Read more</a>
        </li>
        <!-- <li class="purple" style="background-image: url(../assets/images/01.jpg)">
          <h3>She will say “yes”</h3>
          <h2>engagement ring</h2>
          <a href="#" class="btn-more">Read more</a>
        </li>
        <li class="yellow" style="background-image: url(../assets/images/02.jpg)">
          <h3>You deserve to be beauty</h3>
          <h2>golden bracelets</h2>
          <a href="#" class="btn-more">Read more</a>
        </li> -->
      </ul>
    </div>
    <!-- / body -->
    <div id="body">
      <div class="container">
        <div class="last-products">
          <h2>Last added products</h2>
          <section class="products">
            <article>
              <img src="../assets/images/1.jpg" alt="">
              <h3>Excepteur sint occaecat</h3>
              <h4>$1 850.00</h4>
              <a href="cart.html" class="btn-add">Add to cart</a>
            </article>
            <article>
              <img src="../assets/images/11.jpg" alt="">
              <h3>Lorem ipsum dolor</h3>
              <h4>$990.00</h4>
              <a href="cart.html" class="btn-add">Add to cart</a>
            </article>
            <article>
              <img src="../assets/images/12.jpg" alt="">
              <h3>cupidatat non proident</h3>
              <h4>$1 200.00</h4>
              <a href="cart.html" class="btn-add">Add to cart</a>
            </article>
            <article>
              <img src="../assets/images/13.jpg" alt="">
              <h3>Duis aute irure</h3>
              <h4>$2 650.00</h4>
              <a href="cart.html" class="btn-add">Add to cart</a>
            </article>
            <article>
              <img src="../assets/images/14.jpg" alt="">
              <h3>magna aliqua</h3>
              <h4>$3 500.00</h4>
              <a href="cart.html" class="btn-add">Add to cart</a>
            </article>
          </section>
        </div>
        <section class="quick-links">
          <article style="background-image: url(../assets/images/2.jpg)">
            <a href="#" class="table">
              <div class="cell">
                <div class="text">
                  <h4>Lorem ipsum</h4>
                  <hr>
                  <h3>Dolor sit amet</h3>
                </div>
              </div>
            </a>
          </article>
          <article class="red" style="background-image: url(../assets/images/3.jpg)">
            <a href="#" class="table">
              <div class="cell">
                <div class="text">
                  <h4>consequatur</h4>
                  <hr>
                  <h3>voluptatem</h3>
                  <hr>
                  <p>Accusantium</p>
                </div>
              </div>
            </a>
          </article>
          <article style="background-image: url(../assets/images/4.jpg)">
            <a href="#" class="table">
              <div class="cell">
                <div class="text">
                  <h4>culpa qui officia</h4>
                  <hr>
                  <h3>magnam aliquam</h3>
                </div>
              </div>
            </a>
          </article>
        </section>
      </div>
      <!-- / container -->
    </div>
    <!-- / body -->
    <footer id="footer">
      <div class="container">
        <div class="cols">
          <div class="col">
            <h3>Frequently Asked Questions</h3>
            <ul>
              <li><a href="#">Fusce eget dolor adipiscing </a></li>
              <li><a href="#">Posuere nisl eu venenatis gravida</a></li>
              <li><a href="#">Morbi dictum ligula mattis</a></li>
              <li><a href="#">Etiam diam vel dolor luctus dapibus</a></li>
              <li><a href="#">Vestibulum ultrices magna </a></li>
            </ul>
          </div>
          <div class="col media">
            <h3>Social media</h3>
            <ul class="social">
              <li><a href="#"><span class="ico ico-fb" />Facebook</a></li>
              <li><a href="#"><span class="ico ico-tw" />Twitter</a></li>
              <li><a href="#"><span class="ico ico-gp" />Google+</a></li>
              <li><a href="#"><span class="ico ico-pi" />Pinterest</a></li>
            </ul>
          </div>
          <div class="col contact">
            <h3>Contact us</h3>
            <p>Diana’s Jewelry INC.<br>54233 Avenue Street<br>New York</p>
            <p><span class="ico ico-em" /><a href="#">contact@dianasjewelry.com</a></p>
            <p><span class="ico ico-ph" />(590) 423 446 924</p>
          </div>
          <div class="col newsletter">
            <h3>Join our newsletter</h3>
            <p>Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium doloremque laudantium.</p>
            <form action="#">
              <input type="text" placeholder="Your email address...">
              <button type="submit" />
            </form>
          </div>
        </div>
        <p class="copy">
          Copyright 2013 Jewelry. All rights reserved.
        </p>
      </div>
      <!-- / container -->
    </footer>
    <!-- / footer -->
  </div>
</template>
<script>
export default {
  name: "PageIndex"
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
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
