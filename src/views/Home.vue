<template>
  <!-- Header Component -->
  <Header/>

  <!-- Carousel Home Component -->
  <CarouselHome />

  <!-- Home Page Component -->
  <HomePage title="Bem vindo ao compra fone. Compramos seu aparelho com o melhor preço do mercado. Faça uma cotação on-line e saiba quanto vamos pagar."/>

  <!-- Footer Component -->
  <Footer/>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/HeaderComponent.vue";
import Footer from "@/components/FooterComponent.vue";
import HomePage from "@/components/HomePage.vue";
import CarouselHome from "@/components/CarouselHome.vue";

export default {
  name: "Home",
  components: {
    Header,
    CarouselHome,
    HomePage,
    Footer
  }
};
</script>