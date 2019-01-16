<style scoped>
  .carous{
    width: 600px;
    height: 400px;
    margin: 0 auto;
    background-color: #eca;
  }
</style>
<template>
  <Carousel class='carous' autoplay v-model="value2" :autoplay-speed="3000" loop>
    <CarouselItem>
      <div class="demo-carousel">1</div>
    </CarouselItem>
    <CarouselItem>
      <div class="demo-carousel">2</div>
    </CarouselItem>
    <CarouselItem>
      <div class="demo-carousel">3</div>
    </CarouselItem>
    <CarouselItem>
      <div class="demo-carousel">4</div>
    </CarouselItem>
  </Carousel>
</template>
<script>
export default {
  name: 'Home',
  data () {
    return {
      value2: 0
    }
  }
}
</script>
