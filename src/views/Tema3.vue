<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Documentar el proceso de calidad de #[em software]
    
    .cont_3_2
      .cont_3_1.p-4
        .row
          .col-lg-3.mb-3.mb-lg-0(data-aos="fade-right" style="place-self:center;")
            figure.m-auto.col-10.col-md-7.col-lg-12
              img(src="@/assets/curso/tema3/2.png")
          .col-lg-9(data-aos="fade-left" style="place-self:center;")
            .col-xl-10.m-auto.p-3
              p.mb-5.mb-md-0 La documentación de productos de #[em software] son artefactos importantes, dado que estos permiten transferir y comunicar aspectos que al revisar o inspeccionar un sistema no se pueden entender rápidamente y suele ser complicado, por tal razón es que se documenta para comprender, compartir y mostrar el comportamiento y la estructura de un sistema o de sus componentes, controlar y visualizar las arquitectura del sistema y controlar el riesgo, además la documentación debe utilizarse para el desarrollo del producto #[em software] y su mantenimiento en el futuro resaltando que no solo se documenta un proceso respecto a la calidad, sino, también las fases del desarrollo del #[em software], requerimientos, análisis, diseño, construcción y pruebas. Sin embargo, cuando se requiere documentar un proceso de calidad de #[em software] es pertinente tener en cuenta tanto el plan de pruebas como los resultados arrojados que se muestran en los apartados siguientes. 
      
      Separador

      .titulo-segundo(data-aos="zoom-in-right")
        h2#t_3_1 3.1  Diseñar los instrumentos de calidad de #[em software]
      
      .row
        .col(style="place-self:center;" data-aos="fade-right")
          p.mb-0 Los instrumentos de calidad de software, al ser combinados con otras partes, son útiles al momento de realizar mediciones, observar y almacenar datos que sean verificables y que se puedan utilizar para mejoras continuas en los procesos de calidad de un producto. Entonces para documentar pruebas de software, es importante ver el plan de pruebas como un instrumento clave en el diseño y creación de pruebas de software.
        .col-auto(style="place-self:center;" data-aos="fade-left")
          figure
            img(src="@/assets/curso/tema3/5.svg")
      
      .cont_titulo_decorativo.mt-5(data-aos="fade-right")
        .row
          .col-auto.pe-0
            figure.ps-2
              img(src="@/assets/curso/tema2/2.svg")
          .col(style="place-self:center;")
            h4.mb-0.pe-4(style="padding-top:7px;") Plan de pruebas
      
      .row
        .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right" style="place-self:center;")
          p Un instrumento de gran utilidad para estructurar el proceso de pruebas y la documentación es el plan de pruebas. Por lo tanto, la finalidad es suministrar la información requerida para planear y controlar las actividades relacionadas con las pruebas en el proceso de desarrollo de un producto #[em software]. Presenta el enfoque para realizar la verificación de los componentes del producto. Todo proceso de desarrollo de #[em software] debe contar con la implementación de la fase de pruebas. 
          p.mt-4 El personal que se dedica a ejecutar pruebas de #[em software] requiere de un plan de pruebas de #[em software], cuyo objetivo es comunicar a todos los involucrados del proyecto: los entregables, ítems a ser certificados, criterios de aprobación y fallos, criterios de suspensión y reanudación, las necesidades de ambiente, las capacitaciones necesarias para los integrales del equipo, riesgos y el laboratorio de usabilidad.
          .p-3.mt-4(style="background-color:#B3BAD6;border-radius:12px;")
            .row
              .col-auto(style="place-self:center;")
                figure
                  img(src="@/assets/curso/tema3/6.svg")
              .col(style="place-self:center;")
                p.mb-0 El plan se puede aplicar a todo el proyecto y se ajusta a las necesidades de cada empresa, teniendo en cuenta el tamaño del proyecto, el tiempo, el costo, el ciclo de vida del #[em software], los involucrados.
        .col-lg-4(data-aos="fade-left" style="place-self:center;")
          figure.m-auto.col-8.col-md-8.col-lg-12
            img(src="@/assets/curso/tema3/7.png")
    
    p.mt-5(data-aos="fade-right") Cada entidad puede definir su propio plan de pruebas, basados en buenas prácticas, de acuerdo con las siguientes características:



</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>
<style lang="sass">
.cont_3_1, .cont_3_1 *
 position: relative
.cont_3_1:before
  position: absolute
  content: ''
  width: 87%
  right: 0
  height: 82%
  top: auto
  bottom: auto
  background: url(../assets/curso/tema3/1.png)
  background-size: cover
  background-position: center
  border-radius: 12px
.cont_3_2, .cont_3_2 *
 position: relative
.cont_3_2:before
  position: absolute
  content: ''
  width: 125%
  left: -15%
  height: 83%
  top: 13%
  bottom: 7%
  background: url(../assets/curso/tema3/4.png)
  background-size: cover
@media screen and (max-width: 992px)
  .cont_3_1:before
    height: 100%
    width: 100%
    top: 0
  .cont_3_1:before
    background: url(../assets/curso/tema3/3.png)
    background-size: cover
    background-position: center
</style>
