<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .cont_intro1
      p(data-aos="fade-right") Bienvenidos a este componente, en donde trataremos el tema relacionado con los Fundamentos de la calidad del #[em software].
      .row.mt-4
        .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right" style="place-self:center;")
          p Recordemos que implementar buenas prácticas, definir adecuadamente los proceso, ser flexibles ante las diferentes metodologías y herramientas, y tener un personal capacitado en las fases de pruebas y calidad, se convierte en un desafío cada vez más grande, al cual se ven enfrentadas las empresas que construyen #[em software].
          .p-4(style="background-color:#273A89;border-radius:14px;")
            .row
              .col-4.col-md-auto.m-auto(style="place-self:center;")
                figure.mb-4.mb-md-0
                  img(src="@/assets/curso/intro1.svg")
              .col-md.col-12(style="place-self:center;")
                p.mb-0.text-white Dadas las circunstancias actuales, la demanda de construcción de productos de #[em software] va en auge, teniendo un crecimiento exponencial año por año. Si agregamos las iniciativas de modernización de las tecnologías y la tendencia de sistematizar y facilitar los procesos, implica tener más células de desarrollo operando, y mejoras en las fases de calidad del #[em software]. 
        .col-lg-4(data-aos="fade-left" style="place-self:center;")
          figure.m-auto.col-8.col-md-7.col-lg-12
            img(src="@/assets/curso/intro2.png")
      
      .col-xl-10.m-auto.mt-4
        .cont_intro2
          div.d-none.d-lg-block(style="width:100%;bottom:10%;top:10%;position:absolute;right:-5%;")
            figure
              img(src="@/assets/curso/intro4.png")
          .row.p-5.pt-4.pb-4.p-lg-0
            .col-lg-auto.col-md-5.col-7.m-auto(style="place-self:center;" data-aos="fade-right")
              figure.mb-2.mb-lg-0
                img(src="@/assets/curso/intro3.png")
            .col-lg.col-md-12.col-12.p-0.p-lg-4(style="place-self:center;" data-aos="fade-left")
              p.mb-0 En este componente formativo, usted podrá abordar los fundamentos de la calidad del software, entendiendo los valores misionales de las empresas, y cómo estos repercuten en los diferentes procesos de control de la misma. La calidad es una característica que debe ser transversal en todos y cada uno de estos procesos, porque de esta forma podremos asegurar éxito y productividad. Un quipo capacitado, comprometido y creativo es un valor agregado en la industria del software, que cada vez va en aumento, pero que también exige compromiso de todos.

    
 


    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass">
.cont_intro1, .cont_intro1 *
 position: relative
.cont_intro1:before
  position: absolute
  content: ''
  width: 125%
  left: -15%
  height: 100%
  top: auto
  bottom: auto
  background: rgb(220,236,254)
  background: linear-gradient(0deg, rgba(220,236,254,0) 0%, rgba(220,236,254,1) 25%, rgba(220,236,254,1) 75%, rgba(220,236,254,0) 100%)
.cont_intro2, .cont_intro2 *
 position: relative
.cont_intro2:before
  position: absolute
  content: ''
  width: 100%
  right: -5%
  top: 10%
  bottom: 10%
  height: 80%
  background-color: #ADD3FD
  border-radius: 17px
@media screen and (max-width: 992px)
  .cont_intro2:before
    width: 100%
    height: 100%
    right: 0
    top: 0
    bottom: 0
</style>
