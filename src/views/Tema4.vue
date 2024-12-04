<template lang="pug">
.curso-main-container.pb-3
  BannerInterno.fnd-act
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Composición del cuerpo, metabolismo, digestión y absorción
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-3.col-md-6.mb-3
        figure
          img(src='@/assets/curso/temas/tema3/img-10.png')      
      .col-lg-9     
        p El reconocimiento de las necesidades nutricionales calculadas, no son suficientes si no se reconoce el funcionamiento del cuerpo, el cual es particular a cada individuo. La importancia de conocer el concepto de metabolismo, entendido como el conjunto de procesos físicos y químicos que se desarrollan en la célula, radica en la necesidad de identificar fundamentalmente como el organismo convierte los nutrientes de los alimentos en energía necesaria para que el cuerpo cumpla todas las funciones vitales, desde la ingestión del alimento hasta su absorción.
        p De esta manera, esta temática aborda, a partir del conocimiento de la composición básica del cuerpo humano, la comprensión de dos de los procesos fundamentales del metabolismo humano: la digestión y la absorción.

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Composición del cuerpo

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in")
      .col-lg-9     
        p El cuerpo está compuesto de agua distribuida en todos los tejidos, que corresponde aproximadamente a las dos terceras partes del peso corporal de un individuo. Las tres cuartas partes están en el compartimiento intracelular, es decir, en el fluido que está dentro de la célula, mientras la cuarta parte restante se encuentra en el compartimiento extracelular que influye en la circulación sanguínea, la linfa y los fluidos intersticiales que cubren a todas las células. En los tejidos varía el contenido de agua dependiendo de su naturaleza, por ejemplo, los huesos, dientes y el tejido adiposo contienen poca cantidad. 
        p Las proteínas y las grasas constituyen cada una el 18% del peso corporal, variando considerablemente según la cantidad de depósitos de grasa. Por ejemplo, en un bebé recién nácido su reserva adiposa es relativamente baja, pero en un adulto obeso el porcentaje de grasa que puede exceder en un amplio margen al de proteínas. En el cuerpo solamente se encuentran presentes 350 gramos de carbohidratos que son una fuente principal de combustible y sólo una cantidad de éstos se localiza dentro de la estructura de los tejidos.
   
      .col-lg-3.col-md-6
        figure
          img(src='@/assets/curso/temas/tema3/img-11.png')      


    .row.justify-content-center.align-items-center.mb-3(data-aos="fade-right")
      .col-lg-8
        h5 Los elementos químicos predominantes en el cuerpo son:
        figure.mb-4
          img(src='@/assets/curso/temas/tema3/img-12-.svg')           
        p Casi la mayoría de los constituyentes del cuerpo son compuestos orgánicos que se encuentran en cantidades muy pequeñas los cuales no tienen efectos sobre el peso total del cuerpo. Entre estos se encuentran las vitaminas, las hormonas y las enzimas.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-8
        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto
            figure
              img(src='@/assets/curso/temas/tema1/img-4.svg')
          .col.px-0
            h3.mb-0 Las células como unidades de funcionamiento      
        p El cuerpo humano puede estudiarse a varios niveles de organización: el organismo como un todo, los órganos y los tejidos, las células que forman los órganos, los tejidos y los componentes estructurales dentro de las células.
        p Los procesos nutricionales del organismo completo son la suma de las actividades físicas y químicas que tienen lugar dentro de las células y la relación que existe entre estas y el medio que las rodea. El organismo vivo más simple está formado por una célula como es el caso de las bacterias, en cambio, en el organismo más complejo que son los seres humanos las células llevan a cabo sus múltiples actividades, pero no pueden existir independientemente, pues funcionan a través de la coordinación sumamente compleja con otras células.

        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-4.svg')
          .col-auto.px-0
            h3.mb-0 La naturaleza de las enzimas      
        p Todos los seres vivos producen miles de enzimas, sin las cuales la mayoría de las reacciones químicas que se realizan internamente no podrían llevarse a cabo. Las enzimas son catalizadores orgánicos de naturaleza proteica que aumentan considerablemente la velocidad de las reacciones. Cuando una proteína se desnaturaliza por medio del calor, se pierde en muchos casos la actividad de esta.
        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-4.svg')
          .col-auto.px-0
            h3.mb-0 El Metabolismo      
        p El metabolismo es un sinnúmero de reacciones bioquímicas y fisicoquímicas que ocurren en las células y el organismo; en los seres humanos es realizado por enzimas que son generadas por el hígado.         

      .col-lg-4.col-md-6
        figure.mb-4
          img(src='@/assets/curso/temas/tema3/img-13.png')  

      h5 El metabolismo implica la coordinación de varios procesos:          

      .row.justify-content-center.align-items-center.mb-3.fnd-6.p-4(data-aos="zoom-in")
        .col-lg-3.col-md-6.mb-4
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/tema3/img-14.png").img400.m-auto
        .col-lg-9
          SlyderF.custom(columnas="col-lg-6 col-md-6")
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3.text-center Ingestión de alimentos
              p.mb-0 es el primer paso del proceso digestivo, donde los alimentos son introducidos en la boca, masticados y mezclados con saliva. Este proceso forma un bolo alimenticio que se traga y pasa al esófago. Es fundamental para proporcionar al cuerpo los nutrientes necesarios para su funcionamiento adecuado y mantener una buena salud.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              figure.mb-4(data-aos="zoom-in")
                img.img-tar(src="@/assets/curso/temas/tema3/img-15.svg").m-auto
              h5.mb-3.text-center Digestión
              p.mb-0 Es la que prepara los alimentos para ser usados en el cuerpo.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              figure.mb-4(data-aos="zoom-in")
                img.img-tar(src="@/assets/curso/temas/tema3/img-16.svg").m-auto
              h5.mb-3.text-center Absorción
              p.mb-0 Absorción de nutrientes del tracto gastrointestinal a la circulación.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              figure.mb-4(data-aos="zoom-in")
                img.img-tar(src="@/assets/curso/temas/tema3/img-17.svg").m-auto
              h5.mb-3.text-center Transporte de nutrientes
              p.mb-0 De nutrientes por medio del sistema circulatorios a los lugares donde son utilizados y de los desechos a los puntos de excreción.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              figure.mb-4(data-aos="zoom-in")
                img.img-tar(src="@/assets/curso/temas/tema3/img-18.svg").m-auto
              h5.mb-3.text-center Respiración
              p.mb-0 Suministra oxígeno a los alimentos y elimina el dióxido de carbono que se produce como desecho. El sistema respiratorio es de nuevo el responsable del transporte de estos gases.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              figure.mb-4(data-aos="zoom-in")
                img.img-tar(src="@/assets/curso/temas/tema3/img-19.svg").m-auto
              h5.mb-3.text-center Uso de nutrientes
              p.mb-0 Los nutrientes son aprovechados por el organismo en el proceso de oxidación para producir calor y energía, y de esta manera ser usados por las nuevas células y tejidos.
            .tarjeta.tarjeta--slyder.p-4.fnd-5
              h5.mb-3.text-center Excreción de desechos
              p.mb-0 Alimentos no digeridos y ciertos productos del cuerpo se eliminan de diversas formas como por ejemplo : los  pulmones, puede desechar dióxido de carbono y sales minerales, mientras que por medio de los riñones y la piel se eliminan otras sustancias producto del metabolismo.

    .row.justify-content-center.align-items-center.mb-3(data-aos="fade-right")
      .col-lg-9 
        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-4.svg')
          .col-auto.px-0
            h3.mb-0 Digestión
        p La digestión es un proceso que comprende procesos mecánicos y químicos por medio de los cuales los materiales alimenticios complejos son hidrolizados a formas adecuadas para ser absorbidos por la pared de la mucosa y así ser utilizados por el organismo. Sólo unas cuantas sustancias que hacen parte de los alimentos son utilizadas por el cuerpo sin sufrir ningún cambio, estas son: agua, azúcares simples, algunas sales minerales y vitaminas.
        p Uno de los constituyentes en la digestión son las enzimas, pues descomponen los nutrientes de los alimentos ingeridos en compuestos simples para que así puedan ser absorbidos por el organismo. 
        .row.align-items-center
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Controladores del tracto digestivo.
        p La secreción y los jugos gástricos, la actividad motora del tracto y la velocidad de la digestión, son reguladas por factores nerviosos, químicos y físicos. Un ejemplo de esto es el pensamiento, la vista y el aroma de los alimentos; dichos factores hacen que se incremente el flujo de saliva y los jugos gástricos, pero cuando una persona tiene preocupación o miedo, disminuye los jugos gástricos, ocasionando un atraso en la digestión. El sistema nervioso autonómico ejerce continuo control sobre la actividad secretoria y motora en todo el tracto digestivo. La presión de los alimentos contra las membranas mucosas y las características específicas de estos sirven como estímulo a los nervios.
     
      .col-lg-3.col-md-6
        figure.mb-4
          img(src='@/assets/curso/temas/tema3/img-20.png')  
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-12                  
        p <b>Las hormonas son mensajeros químicos que se producen en un punto determinado, como el resultando de un estímulo de alimentos específicos:   </b>
        .titulo-sexto.color-acento-contenido
          h5 Tabla 8.
          span Las hormonas
        .tabla-b.color-acento-contenido.tbl4
          table
            caption Nota. Sena
            thead
              tr
                td Hormonas
                td Donde se produce
                td Estímulo a la secreción
                td Acción
            tbody
              tr
                td Gastrina.
                td Mucosa del píloro y el duodeno.
                td Alimento en el estómago, especialmente proteínas y cafeína, especias y alcoholes.
                td Estimula el flujo del jugo gástrico.
              tr
                td Enterogástrica.
                td Duodeno.
                td Quimo ácido y grasa.
                td Inhibe la secreción del jugo gástrico y reduce la motilidad.
              tr
                td Colecistoquinina.
                td Duodeno.
                td Grasa en el duodeno.
                td Contracción de la vesícula bilar y flujo de bilisalduodeno.
              tr
                td Secretina.
                td Duodeno.
                td Quimo ácido y polipéptidos.
                td Secreción del jugo pancreático delgado, alcalino y pobre en encimas.
              tr
                td Pancreozimina.
                td Duodeno y yeyuno.
                td Quimo ácido y polipéptidos.
                td Secreción del jugo pancreático viscoso, rico en enzimas.
              tr
                td Enterocrinina.
                td Intestino delgado superior.
                td Quimo.
                td Secreción de las glándulas de la mucosa intestinal.

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Digestión mecánica

    p La actividad muscular rítmica hace que los alimentos se reduzcan en partículas diminutas y se mezclen con los jugos gástricos, lo que facilita el movimiento a través del tracto para que haya una superficie mayor de exposición a las enzimas hidrolizantes y al contacto con las paredes absorbentes de la mucosa.

    h6.mb-5 Proceso de digestión mecánica. Motilidad a través del tracto:
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-8
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema3/img-21.png', alt='Proceso de digestión mecánica. Motilidad a través del tracto')
          .tarjeta.color-acento-botones.fnd-10.p-3(x="36.2%" y="17.8%" numero="1")
            p.mb-0 Los alimentos son cortados y molidos en la masticación, luego se mezclan con la saliva y se prepara para ser deglutidos.
            p.ml 01
          .tarjeta.color-acento-botones.fnd-10.p-3(x="51.4%" y="20.2%" numero="2")
            p Mediante las contracciones rítmicas del músculo del esófago dirige las partículas al fondo del estómago (que sirve como recipiente).
            p.ml 02
          .tarjeta.color-acento-botones.fnd-10.p-3(x="49.5%" y="35%" numero="3")
            p El alimento se expande en las paredes del estómago, como hay poca actividad secretora, el alimento permanece en el fondo una hora. En este periodo continúa la digestión salival de los carbohidratos.
            p.ml 03
          .tarjeta.color-acento-botones.fnd-10.p-3(x="60.4%" y="52.5%" numero="4")
            p Se crean pequeñas contracciones en la región central generando intensidad intestinal, el alimento se mezcla con los jugos gástricos y se rompe, reduciéndose a una consistencia delgada semejante a una sopa denominada quimo.
            p.ml 04
          .tarjeta.color-acento-botones.fnd-10.p-3(x="38.4%" y="55.5%" numero="5")
            p La válvula del píloro se abre de tiempo en tiempo permitiendo que pequeñas cantidades de quimo entren el duodeno.
            p.ml 05
          .tarjeta.color-acento-botones.fnd-10.p-3(x="45%" y="60.8%" numero="6")
            p El alimento se expande en las paredes del estómago, como hay poca actividad secretora, el alimento permanece en el fundus durante una hora.
            p.ml 06
          .tarjeta.color-acento-botones.fnd-10.p-3(x="58%" y="67.8%" numero="7")
            p El alimento se mezcla con los jugos gástricos y se rompe reduciéndose a una consistencia delgada semejante a una sopa llamada quimo.
            p.ml 07
          .tarjeta.color-acento-botones.fnd-10.p-3(x="40.9%" y="73.8%" numero="8")
            p La válvula del píloro se abre de tiempo en tiempo permitiendo que pequeñas cantidades de quimo entren en el duodeno, En el intestino delgado las fibras musculares generan contracciones para que el quimo se mezcle con las enzimas digestivas.
            p.ml 08
          .tarjeta.color-acento-botones.fnd-10.p-3(x="58%" y="77.8%" numero="9")
            p A medida que las fibras musculares longitudinales se contraen, se mezclan con la saliva y se preparan para ser deglutidos, entonces se produce el movimiento que lleva la masa del alimento hacia adelante.
            p.ml 09
          .tarjeta.color-acento-botones.fnd-10.p-3(x="47.5%" y="90.8%" numero="10")
            p La masa muscular del tracto también sirve como estímulo a la secreción de los jugos digestivos y aumentan el suministro de sangre a los órganos digestivos.
            p.ml 10
            
    p.mb-4 La velocidad con la que se mueven los alimentos a través del tracto digestivo depende de la consistencia, composición y cantidad del alimento digerido. Por ejemplo, los líquidos empiezan a dejar el estómago 15 minutos después de ser ingeridos, esto explica por qué las dietas líquidas no producen gran saciedad; cuando los carbohidratos se ingieren solos, dejan el estómago más rápido que las proteínas; mientras que las grasas verifican la secreción de jugos gástricos y retardan la actividad peristáltica, de manera que su presencia en las dietas retrasa el vaciado del estómago. Normalmente, el estómago se desocupa en un lapso de tiempo de 4 a 6 horas.              

    .row.justify-content-center.align-items-center.mb-3(data-aos="fade-left")
      .col-lg-4.col-md-6
        figure.mb-4
          img(src='@/assets/curso/temas/tema3/img-22.png') 
      .col-lg-8 
        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-4.svg')
          .col-auto.px-0
            h3.mb-0 Digestión química
        p En diversas regiones del tracto digestivo existe una mezcla compleja que debe hidrolizarse. Dependiendo del lugar, esta incluye materiales alimenticios en varias etapas de hidrólisis, secreciones de fluidos digestivos que contienen enzimas y hormonas, materiales celulares procedentes de la exfoliación de la mucosa, bilis, bacterias y diversos productos del metabolismo dentro del cuerpo que han penetrado en el tracto digestivo.
        p Diariamente, se produce un gran volumen de jugos digestivos en las células secretoras del tracto digestivo, tanto en el páncreas como en el hígado; estos jugos están constituidos por un 98% a un 99% de agua y contienen diversas proporciones de compuestos orgánicos e inorgánicos. Uno de los compuestos inorgánicos más importantes es la mucina, que es una glicoproteína que proporciona al moco la propiedad de ser resbaladizo, facilitando el movimiento suave a lo largo del tracto. 
        p La mayor parte de la actividad hidrolítica sobre los alimentos ocurre en el intestino delgado.

    .titulo-sexto.color-acento-contenido
      h5 Tabla 9.
      span Jugos digestivos y sus acciones
    .tabla-b.color-acento-contenido.tbl5.mb-5.tc2(data-aos="fade-right")
      table
        caption Fuente: Corinne (1985)
        thead
          tr
            td Zona de secreción
            td Estímulo para la secreción
            td Volumen diario y pH
            td Constituyentes importantes
            td Acción
        tbody
          tr
            td <b>Boca:</b> saliva, glándulas salivales, submaxilares, sublinguales, parótidas.
            td <b>Psíquicos:</b> Imaginación, vista, olfato y tacto. <br><b>Mecánicos:</b> Presencia de los alimentos en la boca.<br><b>Químicos:</b> Contacto con el azúcar, sal y especia sobre las papilas.
            td 1000 - 1500 ml, pH 5,9 a 6,8
            td Mucina, Amilasa
            td Lubricación del almidón cocido, dextrinas, maltosa. <br>La actividad enzimática en la boca no es importante.
          tr
            td <b>Estómago:</b> jugo gástrico y células parietales.
            td <b>Psíquicos:</b> Vista, olfato y tacto.<br><b>Mecánicos: </b>Contacto con la mucosa; digestión.<br><b>Hormonales:</b> Gastrina aumenta el flujo y la enterogastrona lo inhibe.
            td 1500-2500 ml, pH 2,0 - 2,5
            td Ácido clorhídrico (HCl)
            td Pepsinógeno, Pepsina, bactericida, reduce el hierro férrico a hierro ferroso.
          tr
            td <b>Células principales.</b>
            td N/A 
            td N/A 
            td Pepsinógeno, Pepsina
            td Forma inactiva de la pepsina.<br>Proteínas, proteasas, peptonas y polipéptidos.
          tr
            td <b>Epitelio columnar.</b>
            td N/A 
            td N/A 
            td Lipasa, Renina (Solo en infantes)
            td Grasas emulsificantes, ácidos grasos más glicerina.<br>Caseína – paracaseína, permite la absorción de la vitamina B12.
          tr
            td <b>Hígado:</b> bilis.
            td La colecistoquinina contrae la vesícula biliar y permite la salida de bilis al duodeno.
            td 500-1100 ml, pH 6,9 a 8,6
            td Sales biliares, pigmentos biliares, colesterol, mucina.
            td Neutraliza el quimo ácido, emulsiona las grasas para que actúe sobre ellas la lipasa, facilitando la absorción de grasas para que actúe sobre ellas la lipasa, facilita la absorción de grasas y vitaminas.

          tr
            td <b>Páncreas: </b>jugo pancreático.
            td Secretina, Pancreozimina
            td 600-3000 ml, pH 7 a 8
            td Jugo delgado, acuoso, alcalino y pobre en enzimas: Amilasa, Quimiotripsinógeno, Quimiotripsina, Tripsinógeno, Tripsina, Peptidasa, Lipasa.
            td Neutraliza el líquido ácido: Almidón dextrinas y maltosas. Forma inactiva de una enzima Proteínas proteasas. Enzima inactiva: polipéptidos Péptidos. Grasas monoglicéridos, ácidos grasos y glicerina.

          tr
            td <b>Intestino delgado:</b> jugo intestinal (succus entericus).
            td <b>Enterocrinina: </b>Presencia de alimentos en el intestino delgado.
            td 2000-3000 ml, pH 7 a 8
            td Enteroquinasa, Peptidasas, Nucleasas, Nucleotidasa, Lecitinasa.
            td Tripsinógeno a tripsina. Polipéptidos a aminoácidos.<br>Ácido nucleico a nucleótidos. Nucleótidos a nucleósidos más fosfato de colina.<br>Lecitina a diglicéridos más fosfato de colina.
          tr
            td <b>Dentro de las células de la mucosa.</b>
            td N/A 
            td N/A 
            td Sacarasa (invertasa), Maltasa, Lactasa
            td Lecitina a diglicéridos más fosfato de colina.<br>Maltosa a glucosa más fructosa.<br>Lactosa a glucosa más galactosa.



    .row.justify-content-center.align-items-center.mb-3(data-aos="fade-right")
      .col-lg-9.order-2.order-lg-1 
        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto.pe-2
            figure
              img(src='@/assets/curso/temas/tema1/img-4.svg')
          .col-auto.px-0
            h3.mb-0 Absorción
        p Es el proceso por el cual los nutrientes se mueven desde el lumen intestinal hasta la sangre, dando como resultado la absorción de nutrientes en el organismo. Es un proceso activo en el cual las sustancias son transportadas dentro del cuerpo; también es un proceso selectivo en el cual algunos materiales como la glucosa es transportada casi en su totalidad a través de las células. Otro ejemplo es el del calcio y el hierro que se absorben solamente de acuerdo con las necesidades del organismo.

        .row.align-items-center
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Punto y velocidad de absorción
        p Se realiza principalmente en el duodeno y el yeyuno; normalmente el 98% de los carbohidratos, el 95% de la grasa y el 92% de la proteína de la dieta se hidrolizan, absorbiéndose los productos finales. Estos porcentajes son conocidos como coeficientes de digestibilidad.
        .row.align-items-center
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Mecanismos de absorción
        p Se conocen tres (3) mecanismos para explicar la absorción:      
      .col-lg-3.col-md-6.order-1.order-lg-2
        figure.mb-4
          img(src='@/assets/curso/temas/tema3/img-23.png')  



    .row.justify-content-center(data-aos="fade-right")
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img-24.png", alt="alt")
          .crd_hover_txt--body
            h6.mb-3 Difusión simple a través de los poros o canales
            p.mb-0 Se realiza cuando las sustancias de muy bajo peso molecular como el agua se pueden mover libremente a través de la membrana, desde el lado de alta concentración hasta el lado de baja concentración. Este proceso es fundamental para el transporte de moléculas pequeñas por la membrana celular y además es uno de los principales mecanismos de la regulación osmótica de las células.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img-25.png", alt="alt")
          .crd_hover_txt--body
            h6.mb-3 Difusión pasiva facilitada por transportadores
            p.mb-0 Los nutrientes que son solubles en agua no pueden penetrar la membrana de la célula que es rica en lípidos, entonces en este proceso entran los llamados transportadores, que son los que facilitan el cruce de estos nutrientes a la membrana celular; esto se conoce como difusión facilitada.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/img-26.png", alt="alt")
          .crd_hover_txt--body
            h6.mb-3 Transporte activo
            p.mb-0.pp1 Se puede decir que la mayor absorción de los nutrientes se lleva a cabo mediante un transporte activo, puesto que es el encargado de bombear los nutrientes hacia arriba y desde el lumen a la circulación, esto quiere decir que los nutrientes se mueven desde un punto de baja concentración a otro de alta concentración. Para que esto funcione se requiere de energía y así realizarse el transporte activo; dicha energía es suministrada por el adenosín trifosfato (ATP) del mecanismo de la glucosa dentro de la célula. El sodio tiene un papel fundamental dentro del transporte activo del agua, azúcares y aminoácidos.





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

<style lang="sass"></style>
