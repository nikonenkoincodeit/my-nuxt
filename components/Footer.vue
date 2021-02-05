<template>
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
            <li>
              <a href="#"><span class="ico ico-fb" />Facebook</a>
            </li>
            <li>
              <a href="#"><span class="ico ico-tw" />Twitter</a>
            </li>
            <li>
              <a href="#"><span class="ico ico-gp" />Google+</a>
            </li>
            <li>
              <a href="#"><span class="ico ico-pi" />Pinterest</a>
            </li>
          </ul>
        </div>
        <div class="col contact">
          <h3>Contact us</h3>
          <p>Diana’s Jewelry INC.<br />54233 Avenue Street<br />New York</p>
          <p>
            <span class="ico ico-em" /><a href="#">contact@dianasjewelry.com</a>
          </p>
          <p><span class="ico ico-ph" />(590) 423 446 924</p>
        </div>
        <div class="col newsletter">
          <h3>Join our newsletter</h3>
          <p>
            Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium
            doloremque laudantium.
          </p>
          <form action="#">
            <input type="text" placeholder="Your email address..." />
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
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
#footer {
  clear: both;
  background: #222224 url(../assets/images/bg_footer.png);
  padding: 27px 0 0;
  color: #a5a5aa;
  font-size: 14px;
  line-height: 30px;
}

#footer h3 {
  color: #fff;
  font-family: "Novecentowide";
  font-size: 14px;
  text-transform: uppercase;
  font-weight: 500;
  padding-bottom: 10px;
}

#footer li:before {
  content: "- ";
}

#footer .ico {
  display: inline-block;
  background: url(../assets/images/ico_footer.png);
  width: 19px;
  height: 19px;
  margin: -5px 10px -5px 0;
}

#footer .ico.ico-tw {
  background-position: 0 -19px;
}

#footer .ico.ico-gp {
  background-position: 0 -38px;
}

#footer .ico.ico-pi {
  background-position: 0 -57px;
}

#footer .ico.ico-em {
  background-position: 0 -76px;
  margin: -7px 7px -7px 0;
}

#footer .ico.ico-ph {
  background-position: 0 -95px;
  margin: -5px 10px -5px -3px;
}

#footer .social li {
  line-height: 32px;
  padding-bottom: 6px;
}

#footer .social li:before {
  display: none;
}

#footer .contact p {
  line-height: 24px;
  font-size: 14px;
  padding: 2px 0 0;
  margin-bottom: 8px;
}

#footer .newsletter p {
  line-height: 24px;
  font-size: 14px;
  padding: 2px 0 0;
  margin-bottom: 8px;
}

#footer form {
  height: 52px;
  margin: 22px 0;
  position: relative;
  background-color: #fff;
}

#footer form button {
  width: 44px;
  height: 44px;
  position: absolute;
  top: 4px;
  right: 4px;
  border: 0;
  background: #b8bcbe url(../assets/images/ico_plus.png) no-repeat 50% 50%;
}

#footer form button:hover {
  opacity: 0.9;
}

#footer form input {
  width: 100%;
  border: 0;
  color: #656567;
  font-size: 14px;
  padding: 15px 75px 15px 25px;
  line-height: normal;
  height: 52px;
  background: #fff;
}

::-webkit-input-placeholder {
  color: #656567;
}

::-moz-placeholder {
  color: #656567;
  opacity: 1;
}

#footer .col {
  float: left;
  width: 25.7%;
  padding-bottom: 37px;
}

#footer .col.media {
  width: 17%;
}

#footer .col.contact {
  width: 25.7%;
}

#footer .col.newsletter {
  width: 31.6%;
}

#footer a {
  color: #a5a5aa;
}

#footer .copy {
  color: #717176;
  font-size: 14px;
  padding: 28px 0;
  clear: both;
  border-top: 1px solid #333336;
}
</style>
