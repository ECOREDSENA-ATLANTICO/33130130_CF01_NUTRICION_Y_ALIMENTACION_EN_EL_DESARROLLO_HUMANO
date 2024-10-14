<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Conceptos fundamentales de nutrición


    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img-1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Muchas veces se habla de estar “bien o mal alimentado” ¿Qué significa eso? ¿A qué se refiere con tener una nutrición acorde con cada persona? Esta primera parte contiene los conceptos fundamentales asociados a la nutrición, los cuales permitirán introducir en el vocabulario personal definiciones acertadas y pertinentes que se utilizarán durante el programa.

    .row.d-flex(data-aos="fade-right")
      .col-lg-6.fnd-3.px-5.py-4.align-items-center.mb-sm-5
        .row.mb-3.pe-lg-5.align-items-center
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-2.png')
          .col-auto.px-0.align-items-center
            h3.mb-0.fnd-2 Alimentación
        p.mb-0 Es el proceso mediante el cual el ser vivo obtiene del entorno una serie de comestibles para ser ingeridos, estos alimentos tienen el propósito de satisfacer el apetito o simplemente deleitar el paladar. La selección de los alimentos es voluntaria y está influida por factores socioeconómicos (disponibilidad de productos), culturales y sicológicos (preferencias).
      .col-lg-6.fnd-4.px-5.py-4.mb-sm-5
        .row.mb-3.pe-lg-5.align-items-center
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-3.png')
          .col-auto.px-0
            h3.mb-0.fnd-2 Nutrientes:
        p Son componentes que se encuentran en los alimentos y que deben ser suministrados al cuerpo en cantidades adecuadas. Estos incluyen agua, proteínas y aminoácidos, que están compuestos de grasas y ácidos grasos, carbohidratos, minerales y vitaminas.

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Nutrición:
    p.mb-5 Es la ciencia que estudia las relaciones entre los nutrientes y el organismo humano a nivel individual y colectivo a lo largo de la vida en diferentes situaciones fisiológicas y patológicas:

    .row.justify-content-center.align-items-center.mb-5.fnd-6.p-4(data-aos="zoom-in")
        .col-lg-3.col-md-8.mb-4
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

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-8

        .nutrition-box.mb-5 
          .cont
            p.mb-0 Buena nutrición es el esfuerzo de múltiples disciplinas y para lograrla se requiere lo siguiente:
            p.mb-0 
              strong La aplicación de la ciencia en la agricultura y la tecnología para producir cantidades suficientes de alimentos vegetales y animales de alto valor nutritivo.
          img.pepper(src="@/assets/curso/temas/tema1/img-6.png")

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Componentes de los alimentos
    p La alimentación entendida como el consumo de alimentos, y actividad necesaria para la subsistencia humana, la cual realizamos desde que se nace:
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-10.f1
        .background
        .cont2
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
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Monosacáridos

    .row.justify-content-center.align-items-center.mb-5.fnd-8.p-lg-5.p-md-3(data-aos="zoom-in")
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
                img(src='@/assets/curso/temas/tema1/img-10.png') 
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
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Disacáridos

    .row.justify-content-center.align-items-center.mb-5.fnd-8-2.p-lg-5.p-md-3(data-aos="fade-right")
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
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Polisacáridos

    p.mb-5 Los polisacáridos están formados por moléculas de diez o más monosacáridos. Se descomponen en moléculas más pequeñas por hidrólisis en el organismo de los seres humanos y tienen la función de mantener reservas de energía.

    .row.d-flex.mb-5(data-aos="fade-left")
      .col-lg-6.fnd-3.px-lg-5.py-lg-4.align-items-center
        .row.mb-3.pe-lg-5.align-items-center
          .col-6
            h5 Almidón
            p.mb-0 este compuesto es un polisacárido que se encuentra en legumbres, cereales como el arroz, en frutas, semillas, en tubérculos como las papas y en las plantas, y cuya función principal es almacenar energía para que los seres humanos puedan digerir con facilidad los almidones. Es necesario cocinarlos o tostarlos, ya que la digestibilidad del almidón depende de la complejidad de las cadenas de glucosa que los forma.
          .col-6          
            figure
              img(src='@/assets/curso/temas/tema1/img-15.png')
      .col-lg-6.fnd-4.px-lg-5.py-lg-4
        .row.pe-lg-5.align-items-center
          .col-6  
            h5 Glucógeno
            p.mb-0 Al igual que el almidón, el glucógeno es un polisacárido que sirve como reserva energética y está conformado por cadenas de glucosa. Es insoluble en el agua y cuando se mezcla con ésta, forma dispersiones de sólidos coloidales. Posterior a la digestión de este carbohidrato se almacena en el hígado y se reparte en menor proporción en los músculos de las personas.
          .col-6          
            figure
              img(src='@/assets/curso/temas/tema1/img-16.png')

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Fibra
    p La fibra es de origen vegetal y se encuentra en las paredes celulares de los vegetales; los componentes más conocidos son: la celulosa, la hemicelulosa, las pectinas y la lignina.
    .row.justify-content-center.align-items-center.mb-5.fl2(data-aos="fade-left")
      .col-lg-5.col-md-8
        figure
          img(src='@/assets/curso/temas/tema1/img-17.png')
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

 
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-10
        .row.align-items-center
          .col-auto.mb-4
            h3.mb-0.fnd-2-1.fnd-2 Alimentación

          .titulo-sexto.color-acento-contenido
            h5 Tabla 1.
            span Efectos de la fibra alimentaria

          .col-lg-12
            .tabla-b.color-acento-contenido.mb-5.tbl
              table
                caption Nota. Sena

                tr
                  td(rowspan='4') Efecto biológico:
                  td.t2.bt1 • Protección frente a las caries.
                  td(rowspan='4') Alimentos ricos en fibra producen:
                  td.t4.bt1 • Mayor masticación y salivación.
                tr
                  td.t2 • Efecto anti nutriente.
                  td.t4 • Absorción de elementos minerales y vitaminas.
                tr
                  td.t2 • Incrementa la absorción de agua sodio de colon.
                  td.t4 • Formación de ácidos grasos de cadena corta (AGCC).
                tr
                  td.t2.bb1 • Protección frente a tóxicos.
                  td.t4.bb1 • Protección de xenobióticos.
        .row.justify-content-center.align-items-center                  
          .col-lg-8
            .row.align-items-center
              .col-auto.mb-3
                h3.mb-0.fnd-2-1.fnd-2 Efectos de la fibra frente a la obesidad:

              p <b>Sensación de saciedad:</b>
              .row.pe-lg-3.row.justify-content-center.align-items-center
                .col-auto.pe-2
                  img(src="@/assets/curso/temas/tema1/check.svg")
                .col.px-0
                  p.mb-0 Dilatación de las paredes del estómago.
              .row.pe-lg-3.row.justify-content-center.align-items-center
                .col-auto.pe-2
                  img(src="@/assets/curso/temas/tema1/check.svg")
                .col.px-0
                  p.mb-0 Reducción del valor calórico.              
              .row.pe-lg-3.row.justify-content-center.align-items-center.mb-4
                .col-auto.pe-2
                  img(src="@/assets/curso/temas/tema1/check.svg")
                .col.px-0
                  p.mb-0 Capacidad de retener agua.

              p.mb-4 <b>Efectos beneficiosos de la fibra alimentaria frente a la diabetes:</b> El requerimiento de insulina en un adulto diabético insulinodependiente tipo l se reduce en un 40% aproximadamente y en uno insulinodependiente tipo II puede llegar a reducirse de un 80% a 100%.
            .row.align-items-center
              .col-auto.mb-3
                h3.mb-0.fnd-2-1.fnd-2 Mecanismos de acción:
              p Disminuye la velocidad de absorción y la cantidad de glucosa absorbida. Los ácidos que se producen por la fermentación favorecen la eliminación de glucosa.

            
          .col-lg-4.col-md-8
            figure
              img(src='@/assets/curso/temas/tema1/img-18.png')


    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Proteínas
      p.mt-4 Las proteínas son sustancias orgánicas que contienen en general una base de elementos químicos como el carbono, el hidrógeno, el oxígeno y el nitrógeno. Están formadas por cadenas lineales de aminoácidos los cuales están encadenados a enlaces peptídicos que se forman en el grupo carboxilo de un aminoácido; son compuestos que desempeñan muchas funciones en los seres humanos y hacen parte de los tejidos, tendones, músculos, piel y uñas, además desempeñan funciones metabólicas, reguladoras y transportan el oxígeno y grasas en la sangre. Hacen parte del código genético (ADN) lo que define la identidad de cada persona.
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-10
        figure.mb-4
          img(src='@/assets/curso/temas/tema1/img-19.svg')

    p.mb-4 A continuación, se describen algunas de estas funciones:

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-3.col-md-8.mb-5
        figure
          img(src='@/assets/curso/temas/tema1/img-20.png')
      .col-lg-9
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul fnd-9")
            div(titulo="Función reguladora:")
              p Algunas proteínas se encargan de regular la cantidad de agua presente en las células a lo que se le conoce como el equilibrio osmótico. Éstas procuran que en la célula no haya ganancia ni pérdida de agua. Las proteínas también son las encargadas de regular el nivel de pH en el interior de estas.
            div(titulo="Función defensiva:")
              p Las proteínas también desempeñan funciones en el sistema inmunológico del cuerpo; por ejemplo, las inmunoglobulinas actúan como anticuerpos frente a agentes patógenos. Proteínas como la trombina o el fibrinógeno ayudan a la formación de coágulos en la sangre, lo que sirve para prevenir hemorragias. Además, algunas proteínas ayudan a eliminar los gérmenes que atacan al cuerpo.
            div(titulo="Función de transporte:")
              p Las proteínas sirven para transportar diferentes sustancias en el interior del cuerpo humano hacia los lugares en donde se necesitan (la hemoglobina es una proteína que se encarga de transportar oxígeno a través de la sangre). En el interior de los músculos el oxígeno es transportado por una proteína llamada la mioglobina. Otro tipo de proteínas llamadas lipoproteínas se encargan de transportar los lípidos en la sangre.
            div(titulo="Función contráctil:")
              p Las proteínas en los músculos son las encargadas de regular los procesos de contracción y estiramiento. Proteínas como la actina y la miosina se encargan de construir las denominadas miofibras de los músculos que son las responsables de las contracciones.



    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-8
        .nutrition-box.mb-5 
          .cont-t
            h2.p-lg-3 Recomendación de ingesta de proteínas
          img.pepper.car1(src="@/assets/curso/temas/tema1/img-21.png")

        .titulo-sexto.color-acento-contenido
          h5 Tabla 2.
          span Efectos de la fibra alimentaria

        .tabla-b.color-acento-contenido.mb-5.tbl2

          table
            caption Nota. Sena
            thead
              tr
                td(colspan='2') Animales
                td(colspan='2') Vegetales y algunos alimentos procesados
            tbody
              tr
                td Leche
                td 3.5 %
                td Legumbres
                td 20 23 %
              tr
                td Queso
                td 15 - 32 % 
                td Frutos secos
                td 15 %
              tr
                td Carne de vacuno
                td 16 - 21 %
                td Pan
                td 8 %
              tr
                td Carne de cerdo
                td 16 - 20 % 
                td Arroz
                td 7 %
              tr
                td Carne de cordero
                td 18 %
                td Pastas
                td 11 %
              tr
                td Carne pollo
                td 21 % P
                td Pastas
                td 5%
              tr
                td Pescados
                td 15 - 25 %
                td Frutas
                td 2.3 %
              tr
                td Huevos
                td 13 % V
                td Verduras de hoja
                td 03 - 1.5 % 

        .titulo-sexto.color-acento-contenido
          h5 Tabla 3.
          span Recomendaciones de proteínas de calidad similar a la del huevo, leche o pescado

        .tabla-b.color-acento-contenido.mb-5.tbl2.tc

          table
            caption Nota. Sena
            thead
              tr
                td Grupo
                td Recomendación g/kg/día
            tbody
              tr
                td Lactantes 0-6 meses
                td 1.47
              tr
                td Lactantes 0,5- 1 año
                td 1.15
              tr
                td Niños 3-4 años
                td 1.09
              tr
                td Niños 9-10 años
                td 0.99
              tr
                td Adolescente 13-14 años (niñas)
                td 0.94
              tr
                td Adolescente 13-14 años (niños)
                td 0.97
              tr
                td Adultos jóvenes (mas 19 años)
                td 0.75
              tr
                td Ancianos
                td 0.75

        .titulo-sexto.color-acento-contenido
          h5 Tabla 4.
          span Necesidades de ingesta de aminoácidos esenciales (mg/kg/día)

        .tabla-b.color-acento-contenido.mb-5.tbl3
          table
            caption Nota. Sena
            thead
              tr
                td Aminoácido
                td Lactantes <br> 3 - 4 meses
                td Niños <br> 2 años
                td Niños <br>10 - 12 años
                td Adultos
            tbody
              tr
                td Histidina
                td 28
                td  
                td  
                td 8.0 - 12.0
              tr
                td Isoleucina
                td 70
                td 31
                td 28
                td 10
              tr
                td Leucina
                td 161
                td 73
                td 44
                td 14
              tr
                td Lisina
                td 103
                td 64
                td 44
                td 12
              tr
                td Metionina y cisteína
                td 58
                td 27
                td 22
                td 13
              tr
                td Fenilalanina y tirosina
                td 125
                td 69
                td 22
                td 14
              tr
                td Treonina
                td 87
                td 37
                td 28
                td 7
              tr
                td Triptófano
                td 17
                td 12.5
                td 3.3
                td 3.5
              tr
                td Valina
                td 93
                td 38
                td 25
                td 10
              tr
                td Total
                td 742
                td 351.5
                td 216.3
                td 93.5
              tr
                td Total, sin histidina
                td 714
                td 351.5
                td 216.3
                td 93.5
              tr
                td.pb-4 Total, de proteína
                td.pb-4 434
                td.pb-4 320
                td.pb-4 222
                td.pb-4 111 

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Lípidos

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-9.order-lg-1.order-2
        p Los lípidos que se ingieren en la dieta están constituidos por fosfolípidos y colesterol. La función más relevante de estos compuestos es dar energía al metabolismo y dar elementos estructurales a la membrana celular. Los lípidos sirven también para transportar las vitaminas liposolubles y son precursores de hormonas y moléculas de señalización celular. Los lípidos en forma de triglicéridos llevan energía a los órganos y músculos internos, pero también pueden ser almacenados como grasa.
        h5 La importancia de los lípidos en la alimentación está relacionada con:
        .row.pe-lg-3.row.justify-content-center.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 Son altamente energéticos y son combustible metabólico, un gramo de grasa equivale a 9 kcal.
        .row.pe-lg-3.row.justify-content-center
          .col-auto.pe-2.pt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 Aportan a la dieta ácidos grasos esenciales como linoleico y alfalinolénico, puesto que estos no son producidos por el organismo.
        .row.pe-lg-3.row.justify-content-center
          .col-auto.pe-2.pt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 Transportan vitaminas liposolubles como A, D, E y K, que se encuentran en el organismo en bajas proporciones y necesitan de los ácidos grasos para formar lipoproteínas en las membranas celulares.

        .row.align-items-center.mt-4
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Clasificación
        p Los lípidos están constituidos por colesterol libre, esterificado, triglicéridos, ácidos grasos libres y fosfolípidos. Estos compuestos están presentes en las lipoproteínas plásticas y son los encargados de transportar los quilomicrones, las lipoproteínas de densidad baja (LDL) y las proteínas de alta densidad (HDL).

      .col-lg-3.col-md-8.order-lg-2.order-1        
        figure
          img(src='@/assets/curso/temas/tema1/img-22.png')

    .row.justify-content-center.align-items-center.mb-5.fnd-8.p-lg-5.p-md-3(data-aos="zoom-in")
      .col-lg-12.fnd-8-1.p-lg-5.p-md-3
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center
            .col-md-8.mb-4.mb-md-0
              h5 Los triglicéridos
              p Estos compuestos son los principales de las grasas naturales; son de baja densidad lo cual les da la característica de almacenar energía en el tejido adiposo. En este grupo se encuentran las grasas saturadas, las cuales cuentan con ácidos grasos sin doble enlace, las monoinsaturadas y las poliinsaturadas. Dichas grasas tienen la propiedad de disminuir los niveles del colesterol LDL; este tipo de colesterol es conocido como el colesterol malo, puesto que es el que perjudica la adecuada circulación de la sangre ya que químicamente contiene lipoproteínas de baja densidad que son dañinas.
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-23.png')

          .row.justify-content-center.align-items-center
            .col-md-8.mb-4.mb-md-0
              h5 Monoinsaturadas
              p Estas grasas se encuentran en los aceites de oliva y girasol, en los frutos secos, en el maíz, en el salmón, el róbalo, la trucha, el pan integral, entre otros. Contienen dentro de su composición el colesterol HDL, conocido también como el colesterol bueno, este ayuda a eliminar los restos de colesterol LDL en la sangre y evita que la grasa se acumule.
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-24.png')

          .row.justify-content-center.align-items-center
            .col-md-8.mb-4.mb-md-0
              h5 Poliinsaturadas
              p También son consideradas grasas saludables para el cuerpo humano, están compuestas por ácidos grasos poliinsaturados en los que los átomos de carbono están unidos por un enlace doble. Entre las grasas poliinsaturadas se encuentra la familia de ácidos omega que son reconocidas por sus efectos positivos en la salud de las personas.
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-25.png')

          .row.justify-content-center.align-items-center
            .col-md-8.mb-4.mb-md-0
              h5 Omega 3, 6 y 9
              p Los ácidos omegas 3 y 6 son ácidos grasos poliinsaturados mientras que el omega 9 es un ácido graso monoinsaturado; se consideran así porque carecen de átomos de hidrógeno. El organismo humano no puede producir estos ácidos, pero sí los necesita para su correcto funcionamiento.
              p Estos ayudan a la formación de las membranas celulares, de las hormonas, del correcto funcionamiento del sistema inmunológico y del funcionamiento de las neuronas.
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-26.png')

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
