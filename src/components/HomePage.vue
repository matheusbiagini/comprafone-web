<template>
    <section id="why-us" class="why-us">
        <div class="container aos-init aos-animate" data-aos="fade-up">
            <div class="row">
                <div class="col-lg-4 d-flex align-items-stretch">
                    <div class="content">
                    <h3>Por que compramos?</h3>
                    <p>
                        Compramos telefones usados, pois temos diversos parceiros que adquirem celulares para reformar e re-vender no mercado. 
                        Hoje o comercio de aparelhos usados é amplo.
                    </p>
                    <div class="text-center">
                        <a href="/about" class="more-btn">Saiba mais <i class="bx bx-chevron-right"></i></a>
                    </div>
                    </div>
                </div>
                <div class="col-lg-8 d-flex align-items-stretch aos-init aos-animate" data-aos="zoom-in" data-aos-delay="100">
                    <div class="icon-boxes d-flex flex-column justify-content-center">
                    <div class="row">
                        <div class="col-xl-4 d-flex align-items-stretch">
                        <div class="icon-box mt-4 mt-xl-0">
                            <i class="bx bx-receipt"></i>
                            <h4>Avaliação de dispositivo</h4>
                            <p>Temos um aplicativo poderoso. Ele é capaz de avaliar se o seu dispositivo tem algum problema físico e estético.</p>
                        </div>
                        </div>
                        <div class="col-xl-4 d-flex align-items-stretch">
                        <div class="icon-box mt-4 mt-xl-0">
                            <i class="bx bx-cube-alt"></i>
                            <h4>Saiba quanto pagamos pelo seu usado</h4>
                            <p>Após nosso aplicativo avaliar seu celular, você fica sabendo quanto vamos te pagar, e decide se quer vender ou não.</p>
                        </div>
                        </div>
                        <div class="col-xl-4 d-flex align-items-stretch">
                        <div class="icon-box mt-4 mt-xl-0">
                            <i class="bx bx-images"></i>
                            <h4>Logística inteligênte</h4>
                            <p>Se decidir vender, nosso aplicativo gera um código de sedex a cobrar, para enviar seu celular sem custo.</p>
                        </div>
                        </div>
                    </div>
                    </div><!-- End .content-->
                </div>
            </div>
        </div>
    </section>

    <section id="counts" class="counts section-bg">
      <div class="container">

        <div class="row counters">

          <div class="col-lg-3 col-6 text-center">
            <span data-purecounter-start="0" data-purecounter-end="1232" data-purecounter-duration="0" class="purecounter">11.232</span>
            <p>Aparelhos comprados</p>
          </div>

          <div class="col-lg-3 col-6 text-center">
            <span data-purecounter-start="0" data-purecounter-end="64" data-purecounter-duration="0" class="purecounter">1964</span>
            <p>Vendedores</p>
          </div>

          <div class="col-lg-3 col-6 text-center">
            <span data-purecounter-start="0" data-purecounter-end="42" data-purecounter-duration="0" class="purecounter">462</span>
            <p>Compradores</p>
          </div>

          <div class="col-lg-3 col-6 text-center">
            <span data-purecounter-start="0" data-purecounter-end="42" data-purecounter-duration="0" class="purecounter">13</span>
            <p>Parceiros</p>
          </div>

        </div>

      </div>
    </section>

    <div class="breadcrumbs aos-init aos-animate" data-aos="fade-in">
      <div class="container">
        <h2>Quem somos</h2>
        <p>Somos um empresa que liga o comprador ao vendedor de forma a tornar a venda e compra do seu aparelho usado mais segura, prática e inteligênte. </p>
      </div>
    </div>

    <br><br>

    <section id="about" class="about">
      <div class="container aos-init aos-animate" data-aos="fade-up">

        <div class="row">
          <div class="col-lg-6 order-1 order-lg-2 aos-init aos-animate" data-aos="fade-left" data-aos-delay="100">
            <img src="@/assets/img/about.jpg" class="img-fluid" alt="">
          </div>
          <div class="col-lg-6 pt-4 pt-lg-0 order-2 order-lg-1 content">
            <h3>Empresa que acredita que a troca de aparelho telefonico não é mais um bicho de 7 cabeças.</h3>
            <p class="fst-italic">
              Prático, rápido e com garantia. Nosso aplicativo une tudo isso para que a venda do seu smartphone sejá rápido.
            </p>
            <ul>
              <li><i class="fa fa-check"></i> Venda seu aplicativo sem precisar sair de casa.</li>
              <li><i class="fa fa-check"></i> Após o envio do seu celular, pagamos em 24h.</li>
              <li><i class="fa fa-check"></i> Você pode acompanhar como está sendo o trâmite de sua negociação.</li>
              <li><i class="fa fa-check"></i> Nossa app pode avaliar como está as condições do seu dispositivo.</li>
            </ul>
            <p>
              Faça nossa avaliação em seu aparelho. É rápido, prático e não leva menos de 5 minutinhos.
            </p>

          </div>
        </div>

      </div>
    </section>
    <br>
</template>

<script>



export default {
  name: "Home",
  props: {
    title: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .why-us .content {
    padding: 30px;
    background: #5fcf80;
    border-radius: 4px;
    color: #fff;
  }
  .why-us .content h3 {
    font-weight: 700;
    font-size: 34px;
    margin-bottom: 30px;
  }
  .why-us .content p {
    margin-bottom: 30px;
  }
  .why-us .content .more-btn {
    display: inline-block;
    background: rgba(255, 255, 255, 0.2);
    padding: 6px 30px 8px 30px;
    color: #fff;
    border-radius: 50px;
    transition: all ease-in-out 0.4s;
  }
  .why-us .content .more-btn i {
    font-size: 14px;
  }
  .why-us .content .more-btn:hover {
    color: #5fcf80;
    background: #fff;
  }
  .why-us .icon-boxes .icon-box {
    text-align: center;
    background: #fff;
    padding: 40px 30px;
    width: 100%;
    border: 1px solid #eef0ef;
  }
  .why-us .icon-boxes .icon-box i {
    font-size: 32px;
    padding: 18px;
    color: #5fcf80;
    margin-bottom: 30px;
    background: #ecf9f0;
    border-radius: 50px;
  }
  .why-us .icon-boxes .icon-box h4 {
    font-size: 20px;
    font-weight: 700;
    margin: 0 0 30px 0;
  }
  .why-us .icon-boxes .icon-box p {
    font-size: 15px;
    color: #848484;
  }

  .counts {
    padding: 30px 0;
  }
  .counts .counters span {
    font-size: 48px;
    display: block;
    color: #5fcf80;
    font-weight: 700;
  }
  .counts .counters p {
    padding: 0;
    margin: 0 0 20px 0;
    font-family: "Raleway", sans-serif;
    font-size: 15px;
    font-weight: 600;
    color: #37423b;
  }
  .about .content h3 {
    font-weight: 600;
    font-size: 26px;
  }
  .about .content ul {
    list-style: none;
    padding: 0;
  }
  .about .content ul li {
    padding-bottom: 10px;
  }
  .about .content ul i {
    font-size: 20px;
    padding-right: 4px;
    color: #5fcf80;
  }
  .about .content .learn-more-btn {
    background: #5fcf80;
    color: #fff;
    border-radius: 50px;
    padding: 8px 25px 9px 25px;
    white-space: nowrap;
    transition: 0.3s;
    font-size: 14px;
    display: inline-block;
  }
  .about .content .learn-more-btn:hover {
    background: #3ac162;
    color: #fff;
  }
  @media (max-width: 768px) {
    .about .content .learn-more-btn {
      margin: 0 48px 0 0;
      padding: 6px 18px;
    }
  }

  .breadcrumbs {
    margin-top: 73px;
    text-align: center;
    background: #5fcf80;
    padding: 30px 0;
    color: #fff;
  }
  @media (max-width: 992px) {
    .breadcrumbs {
      margin-top: 63px;
    }
  }
  .breadcrumbs h2 {
    font-size: 32px;
    font-weight: 500;
  }
  .breadcrumbs p {
    font-size: 14px;
    margin-bottom: 0;
  }

</style>
