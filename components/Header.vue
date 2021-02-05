<template>
  <header id="header">
    <div class="container">
      <a id="logo" href="index.html" title="Diana’s jewelry">Diana’s jewelry</a>
      <div class="right-links">
        <ul>
          <li>
            <a href="cart.html"
              ><span class="ico-products" />3 products, $4 500.00</a
            >
          </li>
          <li>
            <a href="#"><span class="ico-account" />Account</a>
          </li>
          <li>
            <a href="#"><span class="ico-signout" />Sign out</a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style lang="scss" scoped>
#header .container {
  height: 93px;
  padding-top: 20px;
  padding-bottom: 20px;
  border-bottom: 1px solid #dcdcdc;

  .right-links {
    float: right;
    padding: 13px 0 0;
    font-family: "Novecentowide";
  }

  .right-links span {
    float: left;
    width: 20px;
    height: 20px;
    margin: 5px 12px 0 0;
    background: url(../assets/images/ico_header.png) no-repeat;
  }
  .right-links span.ico-account {
    background-position: -20px 0;
  }
  .right-links span.ico-signout {
    background-position: -40px 0;
  }
  .right-links li {
    float: left;
    color: #656567;
    font-weight: 500;
    padding-left: 37px;
    font-size: 12px;
  }
  .right-links a {
    color: #656567;
  }
}

#logo {
  width: 197px;
  height: 52px;
  display: block;
  float: left;
  cursor: pointer;
  text-indent: -9999em;
  background: url(../assets/images/logo.png) no-repeat;
}
</style>
