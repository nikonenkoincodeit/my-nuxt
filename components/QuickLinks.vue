<template>
  <section class="quick-links d-flex">
    <article>
      <a href="#" class="table">
        <div class="cell">
          <div class="text">
            <h4>Lorem ipsum</h4>
            <hr />
            <h3>Dolor sit amet</h3>
          </div>
        </div>
      </a>
    </article>

    <article class="red">
      <a href="#" class="table">
        <div class="cell">
          <div class="text">
            <h4>consequatur</h4>
            <hr />
            <h3>voluptatem</h3>
            <hr />
            <p>Accusantium</p>
          </div>
        </div>
      </a>
    </article>

    <article>
      <a href="#" class="table">
        <div class="cell">
          <div class="text">
            <h4>culpa qui officia</h4>
            <hr />
            <h3>magnam aliquam</h3>
          </div>
        </div>
      </a>
    </article>
  </section>
</template>

<script>
export default {
  name: "QuickLinks"
};
</script>

<style lang="scss" scoped>
.quick-links {
  $indexs: 1, 2, 3;
  @each $index in $indexs {
    article:nth-child(#{$index}) {
      background: url(../assets/images/#{$index+1}.jpg);
    }
  }
}
</style>
