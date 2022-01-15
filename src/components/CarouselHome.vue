<template>
  <Carousel :autoplay="2000" :wrap-around="true">
    <Slide v-for="item in items" :key="item">

      <div class="carousel__item" 
        :style="{
          minHeight: '400px',
          backgroundImage: 'url(\'' + item.src + '\')',
          backgroundPosition: 'center center',
          backgroundSize: 'cover',
          color: item.colorText
        }">
        {{ item.text }}
      </div>
    </Slide>

    <template #addons>
      <Pagination />
    </template>
  </Carousel>
</template>

<script>
import { defineComponent } from 'vue'
import { Carousel, Pagination, Slide } from 'vue3-carousel';

import 'vue3-carousel/dist/carousel.css';

export default defineComponent({
  name: 'CarouselHome',
  components: {
    Carousel,
    Slide,
    Pagination,
  },
  data() {
    return {
      items: [
        { 
          src: require('@/assets/img/carousel/img-01.png'),
          text: 'Faça uma avaliação do seu aparelho e saiba quanto vamos pagar por ele.',
          colorText: '#FFF'
        },
        { 
          src: require('@/assets/img/carousel/img-02.png'),
          text: 'Venha vender seu celular, pagamos o melhor preço de mercado em seu usado.',
          colorText: '#000'
        },
      ]
    }
  },
  methods: {
   pathItem(item) {
      return item;
   }
}
});
</script>

<style>
.carousel__item {  
  min-height: 500px;
  width: 100%;
  background-color: #343d46;
  color:  var(--vc-clr-white);
  font-size: 20px;
  border-radius: 2px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px
}

.carousel__slide {
  padding: 0px;
}

.carousel__pagination-button{
   background-color: #343d46; 
}

.carousel__prev,
.carousel__next {
  box-sizing: content-box;
  border: 2px solid white;
}
</style>