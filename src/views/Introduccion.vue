<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p Bienvenidos al programa de estudio sobre nutrición y alimentación. A lo largo de esta unidad, exploraremos cómo el desarrollo del cuerpo humano está profundamente vinculado a la calidad de la nutrición desde el momento de la concepción. Una alimentación adecuada no solo garantiza el suministro de nutrientes esenciales, sino que también asegura el óptimo funcionamiento de nuestros órganos y, por ende, nuestra salud.
    .cajon.color-secundario.p-4.mb-4.fnd-1
      p Para comprender la importancia de la nutrición, es fundamental familiarizarnos con los componentes básicos de los alimentos, como carbohidratos, proteínas, lípidos, vitaminas y minerales, y entender cómo cada uno de ellos contribuye al bienestar general. Durante este curso, nos centraremos en estos componentes y su rol en una dieta equilibrada.
      p.mb-0 Además, abordaremos temas clave como el valor energético de los alimentos, el gasto energético y los procesos vitales de metabolismo, digestión y absorción. Esta base teórica te proporcionará las herramientas necesarias para aplicar tus conocimientos de manera efectiva en la práctica. Bienvenido a este componente formativo:
    
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/fexKM5o_zm0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Sena (2024).
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
