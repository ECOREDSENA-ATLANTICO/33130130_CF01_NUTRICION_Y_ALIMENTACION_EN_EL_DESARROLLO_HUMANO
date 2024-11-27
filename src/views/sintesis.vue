<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 La nutrición se basa en principios fundamentales que destacan la importancia de los macronutrientes (carbohidratos, proteínas y grasas) y micronutrientes (vitaminas y minerales) para mantener una dieta equilibrada y la salud. Las vitaminas son esenciales, cada una cumpliendo funciones específicas en el organismo, y su deficiencia o exceso puede tener graves consecuencias para la salud. Los alimentos aportan energía, medida en calorías, que el cuerpo utiliza para realizar diversas funciones vitales. Además, la composición del cuerpo humano y los procesos de metabolismo, digestión y absorción de nutrientes son cruciales para garantizar que los alimentos se utilicen de manera efectiva.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis de este programa se detalla los componentes de los alimentos, que incluye los conceptos fundamentales de nutrición y los alimentos.Así mismo los que producen el gasto energético y fisiología de la nutrición. ")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
