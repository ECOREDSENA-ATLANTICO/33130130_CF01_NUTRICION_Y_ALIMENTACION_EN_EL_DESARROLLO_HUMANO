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

    .row.d-flex.mb-5
      .col-lg-6.fnd-3.px-lg-5.py-lg-4.align-items-center
        .row.mb-3.pe-lg-5.align-items-center
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-2.png', alt='')
          .col-auto.px-0.align-items-center
            h3.mb-0.fnd-2 Alimentación
        p.mb-0 Es el proceso mediante el cual el ser vivo obtiene del entorno una serie de comestibles para ser ingeridos, estos alimentos tienen el propósito de satisfacer el apetito o simplemente deleitar el paladar. La selección de los alimentos es voluntaria y está influida por factores socioeconómicos (disponibilidad de productos), culturales y sicológicos (preferencias).
      .col-lg-6.fnd-4.px-lg-5.py-lg-4
        .row.mb-3.pe-lg-5.align-items-center
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-3.png', alt='')
          .col-auto.px-0
            h3.mb-0.fnd-2 Nutrientes:
        p Son componentes que se encuentran en los alimentos y que deben ser suministrados al cuerpo en cantidades adecuadas. Estos incluyen agua, proteínas y aminoácidos, que están compuestos de grasas y ácidos grasos, carbohidratos, minerales y vitaminas.

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg', alt='')
      .col-auto.px-0
        h3.mb-0 Nutrición:
    p.mb-5 Es la ciencia que estudia las relaciones entre los nutrientes y el organismo humano a nivel individual y colectivo a lo largo de la vida en diferentes situaciones fisiológicas y patológicas:

    .row.justify-content-center.align-items-center.mb-5.fnd-6.p-4(data-aos="zoom-in")
        .col-lg-3.col-sm-6.mb-4
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/tema1/img-5.png").img400.m-auto
        .col-lg-9
          SlyderF.custom(columnas="col-lg-6 col-md-6")
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Nutrición básica:
              p.mb-0 Busca proporcionar al cuerpo los nutrientes necesarios para una buena salud. Es la reposición de energía y sustancias pérdidas o gastadas por la actividad diaria.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Nutrición comunitaria:
              p.mb-0 Conjunto de actividades vinculadas a la salud pública que, dentro del marco de la nutrición aplicada y la promoción de la salud, se desarrollan en un hábitat determinado y con un enfoque participativo en la comunidad.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Nutrición clínica:
              p.mb-0 La nutrición clínica es la parte de la medicina que se ocupa de atender a aquellos pacientes que padecen enfermedades en las que una alimentación adecuada forma parte de su tratamiento. En el ámbito de la medicina preventiva, la nutrición clínica da consejos para prevenir la aparición de enfermedades vinculadas a una alimentación inadecuada.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Estado nutricional:
              p.mb-0 Este puede determinarse correlacionando la información que se obtiene a través de una historia clínica y dietética, un análisis físico completo e investigaciones de laboratorio adecuadas.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Buena nutrición:
              p.mb-0 Este término hace referencia a las cantidades correctas de nutrientes esenciales que necesitan los seres humanos para obtener un buen desarrollo físico y mental a través de todo el ciclo de vida.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Mala nutrición:
              p.mb-0 Se refiere al deterioro de la salud que se presenta como consecuencia de una deficiencia, exceso o desequilibrio de nutrientes. En la mala nutrición influyen factores como la desnutrición por deficiencia de calorías o de nutrientes esenciales; también se puede dar por el exceso nutrientes.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3 Buena nutrición:
              p.mb-0 Es el esfuerzo de múltiples disciplinas y para lograrla se requiere lo siguiente: - La aplicación de la ciencia en la agricultura y la tecnología para producir cantidades suficientes de alimentos vegetales y animales de alto valor nutritivo.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8

        .nutrition-box.mb-5 
          .content
            p.mb-0 Buena nutrición es el esfuerzo de múltiples disciplinas y para lograrla se requiere lo siguiente:
            p.mb-0 
              strong La aplicación de la ciencia en la agricultura y la tecnología para producir cantidades suficientes de alimentos vegetales y animales de alto valor nutritivo.
          img.pepper(src="@/assets/curso/temas/tema1/img-6.png")

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg', alt='')
      .col-auto.px-0
        h3.mb-0 Componentes de los alimentos
    p La alimentación entendida como el consumo de alimentos, y actividad necesaria para la subsistencia humana, la cual realizamos desde que se nace:
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.f1
            .background
            .content
              .row.justify-content-center.d-flex
                .col-sm-6.col-xl-5.mb-4.mb-xl-0
                  .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
                    .indicador--hover(v-if="indicadorTarjetaFlip")
                    .tarjeta-flip__contenedor
                      .tarjeta-flip__img.fl1(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img-7.png')})`}")
                      .tarjeta-flip__contenido.p-4.p-xl-5.fnd-7
                        h5.text-center Función Principal  
                        p.text-center Energética; permite mantener en correcto funcionamiento la actividad de los músculos, la presión arterial, la temperatura del cuerpo, las funciones de los órganos internos y especialmente hace que el cerebro y el sistema nervioso central operen adecuadamente.   
              
                .col-sm-6.col-xl-5.mb-4.mb-xl-0
                  .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
                    .indicador--hover(v-if="indicadorTarjetaFlip")
                    .tarjeta-flip__contenedor
                      .tarjeta-flip__img.fl1(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img-8.png')})`}")
                      .tarjeta-flip__contenido.p-4.p-xl-5.fnd-7
                        h5.text-center.mt-lg-5 Otras funciones o compuestos mixtos:
                        .row.pe-lg-3.row.justify-content-center.align-items-center
                          .col-auto.pe-2
                            img(src="@/assets/curso/temas/tema1/check.svg")
                          .col.px-0
                            p.mb-0 <b>Proteoglicanos:</b> Función estructural.
                        .row.pe-lg-3.row.justify-content-center.align-items-center
                          .col-auto.pe-2
                            img(src="@/assets/curso/temas/tema1/check.svg")
                          .col.px-0
                            p.mb-0 <b>Glucoproteínas:</b> Función reguladora.
                        .row.pe-lg-3.row.justify-content-center.align-items-center
                          .col-auto.pe-2
                            img(src="@/assets/curso/temas/tema1/check.svg")
                          .col.px-0
                            p.mb-0 <b>Glucolípidos:</b> Función en el tejido nervioso, cerebrósidos y gangliósidos.
      
                  

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg', alt='')
      .col-auto.px-0
        h3.mb-0 Monosacáridos

    .row.justify-content-center.align-items-center.mb-5.fnd-8.p-lg-5.p-md-3
      .col-lg-12.fnd-8-1.p-lg-5.p-md-3
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center
            .col-md-6.mb-4.mb-md-0
              h5 Glucosa:	
              p Este compuesto es monosacárido y es muy importante para la sangre de los seres humanos. Por lo general los hidratos de carbono que son consumidos por las personas son transformados en el hígado en glucosa, que es la única fuente de energía para las neuronas (en condiciones normales), células sanguíneas y médula renal; además, es la principal fuente energética para los tejidos muscular y adiposo.

          
            .col-md-6
              figure
                img.img-262(src='@/assets/curso/temas/tema1/img-9.png')
          .row.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              h5 Fructosa:	
              p Monosacárido que por lo general se encuentra en las frutas y tiene seis átomos de carbono, la fructosa es transformada en el hígado en glucosa para dar energía a las células
          
            .col-md-8
              figure
                img.img-262(src='@/assets/curso/temas/tema1/img-10.png') 
          .row.justify-content-center.align-items-center
            .col-md-4.mb-4.mb-md-0
              h5 Galactosa:	
              p Se obtiene por hidrólisis de la lactosa; es un monosacárido de seis átomos de carbono. En el cuerpo de los seres humanos se transforma en glucosa y cumple la función de apoyar la actividad de las células cerebrales. 
          
            .col-md-8
              figure
                img.img-262(src='@/assets/curso/temas/tema1/img-11.png')                            
 

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg', alt='')
      .col-auto.px-0
        h3.mb-0 Disacáridos

    .row.justify-content-center.align-items-center.mb-5.fnd-8-2.p-lg-5.p-md-3
      .col-lg-12.fnd-8-1.p-lg-5.p-md-3
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center
            .col-md-6.mb-4.mb-md-0
              h5 Lactosa:	
              p Disacárido que se encuentra en la leche que por hidrólisis da como resultado monosacáridos como glucosa y galactosa. La lactosa comúnmente se conoce como el azúcar de la leche; este producto es muy importante para los lactantes porque aporta energía y nutrientes. En las personas adultas aporta energía.
            .col-md-6
              figure
                img.img-262(src='@/assets/curso/temas/tema1/img-12.png') 
          .row.justify-content-center.align-items-center
            .col-md-5.mb-4.mb-md-0
              h5 Sacarosa:	
              p Es un disacárido conocido comúnmente como el azúcar de mesa, es extraído de la caña de azúcar y de la remolacha; por la acción de la hidrólisis en la digestión da como resultado una glucosa más una fructosa. Este producto es muy usado para endulzar comidas y bebidas, cuando es absorbida por el cuerpo genera un incremento rápido de la energía.	 
            .col-md-7
              figure
                img.img-262(src='@/assets/curso/temas/tema1/img-13.png')               
          .row.justify-content-center.align-items-center
            .col-md-5.mb-4.mb-md-0
              h5 Maltosa:	
              p Es un disacárido que se encuentra en los germinados de algunos cereales como cebada y maíz. La maltosa se puede obtener de la hidrólisis del almidón por presencia de enzimas llamadas amilasas. La maltosa está formada por D-glucosa y se conoce como un azúcar reductor porque posee un grupo carbonilo libre que puede oxidarse con facilidad.
            .col-md-7
              figure
                img.img-262(src='@/assets/curso/temas/tema1/img-14.png')                             
       
   
    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg', alt='')
      .col-auto.px-0
        h3.mb-0 Polisacáridos

    p.mb-5 Los polisacáridos están formados por moléculas de diez o más monosacáridos. Se descomponen en moléculas más pequeñas por hidrólisis en el organismo de los seres humanos y tienen la función de mantener reservas de energía.

    .row.d-flex.mb-5
      .col-lg-6.fnd-3.px-lg-5.py-lg-4.align-items-center
        .row.mb-3.pe-lg-5.align-items-center
          .col-6
            h5 Almidón
            p.mb-0 este compuesto es un polisacárido que se encuentra en legumbres, cereales como el arroz, en frutas, semillas, en tubérculos como las papas y en las plantas, y cuya función principal es almacenar energía para que los seres humanos puedan digerir con facilidad los almidones. Es necesario cocinarlos o tostarlos, ya que la digestibilidad del almidón depende de la complejidad de las cadenas de glucosa que los forma.
          .col-6          
            figure
              img(src='@/assets/curso/temas/tema1/img-15.png', alt='')
      .col-lg-6.fnd-4.px-lg-5.py-lg-4
        .row.pe-lg-5.align-items-center
          .col-6  
            h5 Glucógeno
            p.mb-0 Al igual que el almidón, el glucógeno es un polisacárido que sirve como reserva energética y está conformado por cadenas de glucosa. Es insoluble en el agua y cuando se mezcla con ésta, forma dispersiones de sólidos coloidales. Posterior a la digestión de este carbohidrato se almacena en el hígado y se reparte en menor proporción en los músculos de las personas.
          .col-6          
            figure
              img(src='@/assets/curso/temas/tema1/img-16.png', alt='')

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg', alt='')
      .col-auto.px-0
        h3.mb-0 Fibra
    p La fibra es de origen vegetal y se encuentra en las paredes celulares de los vegetales; los componentes más conocidos son: la celulosa, la hemicelulosa, las pectinas y la lignina.
    .row.justify-content-center.align-items-center.mb-5.fl2
      .col-lg-5.col-md-8
        figure
          img(src='@/assets/curso/temas/tema1/img-17.png', alt='')
      .col-lg-7.p-md-3.p-xl-5
        h5.mb-0 Intestino delgado
        p.mb-0 Aumento del volumen y viscosidad del bolo (fibra soluble):
        p.mb-0 - Retraso de la digestión y enlentecimiento de la absorción intestinal.
        p.mb-0 - Aumento de absorción en enterocitos distales.
        p - Disminuye la demanda de insulina porque reduce la liberación del polipéptido inhibidor gástrico.
        h5.mb-0 Aumento del tránsito (fibra soluble)
        p - Parte de los carbohidratos que se absorben mal.
        h5.mb-0 Intestino grueso
        p.mb-0 - Incremento de la motilidad:
        p.mb-0 - Por acción mecánica y química.
        p.mb-0 - Dilución de otros componentes de los alimentos.
        p.mb-0 - Efectos derivados del metabolismo de los componentes de la fibra.

 










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
