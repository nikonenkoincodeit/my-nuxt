<template>
  <div>
    <b-carousel
      id="carousel"
      style="text-shadow: 0px 0px 2px #000"
      indicators
      fade
    >
      <b-carousel-slide
        v-for="img in images"
        :key="img"
        :img-src="require(`../assets/images/${img}`)"
      ></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: "Slider",
  data: () => ({
    images: ["rings.jpg", "01.jpg", "02.jpg"]
  })
};
</script>

<style lang="scss">
#carousel {
  width: 100vw;
  .carousel-indicators li {
    border-radius: 50%;
    overflow: hidden;
    width: 13px;
    height: 13px;
    border: 2px solid #fff;
    box-sizing: border-box;
    background: transparent;
    opacity: 1;
  }
  .carousel-indicators li.active {
    background: #fff;
  }
}
.carousel-indicators {
  height: 32px;
  margin-bottom: 10px;

  li:focus {
    outline: none;
  }
}
</style>
