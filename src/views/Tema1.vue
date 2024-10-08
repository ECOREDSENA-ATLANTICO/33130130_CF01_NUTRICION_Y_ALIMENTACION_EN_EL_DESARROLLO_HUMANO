<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Conceptos fundamentales de nutrición


    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img-1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Muchas veces se habla de estar “bien o mal alimentado” ¿Qué significa eso? ¿A qué se refiere con tener una nutrición acorde con cada persona? Esta primera parte contiene los conceptos fundamentales asociados a la nutrición, los cuales permitirán introducir en el vocabulario personal definiciones acertadas y pertinentes que se utilizarán durante el programa.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        .row.mb-4.pe-lg-3.align-items-center
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-2.png', alt='')
          .col-auto.px-0
            h3.mb-0.fnd-2 Alimentación
        p Es el proceso mediante el cual el ser vivo obtiene del entorno una serie de comestibles para ser ingeridos, estos alimentos tienen el propósito de satisfacer el apetito o simplemente deleitar el paladar. La selección de los alimentos es voluntaria y está influida por factores socioeconómicos (disponibilidad de productos), culturales y sicológicos (preferencias).

    p •	Nutrientes:
    p Son componentes que se encuentran en los alimentos y que deben ser suministrados al cuerpo en cantidades adecuadas. Estos incluyen agua, proteínas y aminoácidos, que están compuestos de grasas y ácidos grasos, carbohidratos, minerales y vitaminas.


    p •	Nutrición:
    p Es la ciencia que estudia las relaciones entre los nutrientes y el organismo humano a nivel individual y colectivo a lo largo de la vida en diferentes situaciones fisiológicas y patológicas:



</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

<style lang="sass"></style>
