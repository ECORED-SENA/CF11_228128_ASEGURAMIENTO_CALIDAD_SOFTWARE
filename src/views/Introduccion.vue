<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p(data-aos="fade-right") Bienvenidos a este componente, en donde trataremos el tema relacionado con los Fundamentos de la calidad del #[em software].
    p.mt-4(data-aos="fade-left") Recordemos que implementar buenas prácticas, definir adecuadamente los proceso, ser flexibles ante las diferentes metodologías y herramientas, y tener un personal capacitado en las fases de pruebas y calidad, se convierte en un desafío cada vez más grande, al cual se ven enfrentadas las empresas que construyen #[em software].

    .p-4.mt-4(style="background-color:#BAE9D9;")
      .cont_intro1.p-3
        .row
          .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right" style="place-self:center;")
            figure.m-auto.col-6.col-md-6.col-lg-12
              img(src="@/assets/curso/intro1.png")
          .col-lg-9(data-aos="fade-left" style="place-self:center;")
            .p-lg-4
              p Dadas las circunstancias actuales, la demanda de construcción de productos de software va en auge, teniendo un crecimiento exponencial año por año. Si agregamos las iniciativas de modernización de las tecnologías y la tendencia de sistematizar y facilitar los procesos, implica tener más células de desarrollo operando, y mejoras en las fases de calidad del #[em software]. 
              p.mt-4.mb-0 En este componente formativo, usted podrá abordar los fundamentos de la calidad del software, entendiendo los valores misionales de las empresas, y cómo estos repercuten en los diferentes procesos de control de la misma. La calidad es una característica que debe ser transversal en todos y cada uno de estos procesos, porque de esta forma podremos asegurar éxito y productividad. Un quipo capacitado, comprometido y creativo es un valor agregado en la industria del software, que cada vez va en aumento, pero que también exige compromiso de todos.

    
 


    
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
  width: 87%
  right: 0
  height: 90%
  top: auto
  bottom: auto
  border-radius: 12px
  background-color: #fff
@media screen and (max-width: 992px)
  .cont_intro1:before
    height: 100%
    width: 100%
    top: 0
</style>
