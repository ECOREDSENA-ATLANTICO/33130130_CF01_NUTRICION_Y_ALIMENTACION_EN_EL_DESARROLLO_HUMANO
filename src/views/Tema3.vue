<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 El valor energético de los alimentos

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-3.col-md-6.mb-md-5
        figure
          img(src='@/assets/curso/temas/tema3/img-1.png')           
          
      .col-lg-9
        .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
          .col-auto.pe-2      
        p.mb-5  El valor energético de un alimento es la cantidad de energía que éste aporta al cuerpo humano y resulta de la combustión de los lípidos, proteínas y glúcidos. Esta energía es utilizada por el cuerpo para mantener la temperatura y realizar todas sus funciones; se expresa en calorías (cal) o kilocalorías (kcal), es importante tener presente que la caloría es una medida de calor que consiste en transferir calor físicamente para aumentar la temperatura de un gramo de agua en un grado, entonces se puede decir que una kilocaloría equivale a 1000 calorías.
        p.mb-0  La dieta de las personas adultas está compuesta de 1000 a 5000 kilocalorías por día. Todos los nutrientes presentes en los alimentos tienen un valor energético diferente, por eso se toman valores estándar para cada grupo, por ejemplo, un gramo de un glúcido al quemarse libera cuatro (4) kilocalorías, lo mismo ocurre con las proteínas que liberan cuatro (4) kilocalorías, en cambio las grasas al quemarse producen nueve (9) kilocalorías, por eso los alimentos ricos en grasas constituyen un aporte mayor en cuanto a su contenido energético. La reserva de energía que el cuerpo humano almacena es en forma de grasa.


    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in")
      .col-lg-12
        figure
          img(src='@/assets/curso/temas/tema3/img-2.svg')       

    .row(data-aos="zoom-in")
      .col-auto.mb-3
        h3.mb-0.fnd-2-1.fnd-2 Tablas de composición de los alimentos.
    .row.justify-content-center.align-items-center.mb-2(data-aos="fade-right")
      .col-lg-9
        p En las tablas de composición de un alimento está descrito cuántas kilocalorías tiene un alimento y cuánto tiene de proteínas, lípidos y glúcidos. Entonces para saber el total de calorías de un alimento se debe saber cuántos gramos de cada nutriente contiene para después multiplicarlo por el valor calórico, por ejemplo, una porción de helado tiene:
        .row.mb-4.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Proteínas:</b> 4 gramos. Entonces se multiplica (4 g x 4 kcal/g) = 16 kcal.
        .row.mb-4.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Grasas:</b> 12 gramos. Entonces se multiplica (12 g x 9 kcal/g) = 108 kcal.                
        .row.mb-4.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Glúcidos:</b> 19 gramos. Entonces se multiplica (19 gr x 4 kcal/g) = 76 kcal.             
        .row.mb-4.pe-lg-3.align-items-center.mb-4
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Calorías totales:</b> 200 kcal.                  

        p.mb-4 Necesidades energéticas del ser humano y el valor energético de los Alimentos. El consumo diario de energía depende de lo que requiera el cuerpo. Cuando sehabla de consumo diario se hace referencia a la cantidad de energía que gasta elcuerpo para suplir todas sus necesidades; este factor se llama Gasto calórico total.
        p.mb-3 Los requerimientos diarios de energía se calculan como la suma de los siguientes factores:
                  
      .col-lg-3.col-md-6.mb-md-5
        figure
          img(src='@/assets/curso/temas/tema3/img-3.png')
          
    .titulo-sexto.color-acento-contenido(data-aos="fade-left")
      h5 Tabla 6.
      span Requerimientos diarios de energía

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-auto
        .bodytabla.tabla-a
          table
            caption Nota. FAO (2017)
            tr
              td Metabolismo basal.
              td 60%
              td Efecto térmico de los alimentos (digestión de los alimentos y absorción de nutrientes).
              td 30%
              td Actividad física.
              td 10%
              td Gasto total de energía durante el día.
              td 100%

    .row(data-aos="fade-right")
      .col-auto.mb-3
        h3.mb-0.fnd-2-1.fnd-2 Tasa de Metabolismo basal (TMB):     


    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-3.col-md-6.mb-3
        figure
          img(src='@/assets/curso/temas/tema3/img-5.png')
      .col-lg-9
        p Hace referencia a la cantidad mínima de energía que el organismo requiere para que el cuerpo se mantenga despierto o en reposo y cumplir todas sus actividades vitales como respiración, presión arterial, latidos del corazón, entre otras. El metabolismo basal depende de factores como:
        .row.mb-3.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Sexo:</b>Los hombres tienen mayor metabolismo basal que las mujeres.
        .row.mb-3.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Talla:</b>Las personas altas tienen mayor metabolismo basal que las bajas.    
        .row.mb-3.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Peso: </b>Cuando se tiene un mayor peso, se requiere de más metabolismo basal.
        .row.mb-3.pe-lg-3.align-items-center
          .col-auto.pe-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Edad:</b>Entre más joven, el metabolismo basal es más alto, esto se debe al crecimiento. 
        p.mb-4 Una fórmula muy utilizada para calcular la TMR es la de Harris - Benedict a partir del peso (P) (kg) y de la talla (T) (cm): 

      .col-lg-10
        figure.mb-5
          img(src='@/assets/curso/temas/tema3/img-6.svg')         

        p.mb-5 A este cálculo se le añade un factor de corrección en función del ejercicio físico realizado:

        .titulo-sexto.color-acento-contenido
          h5 Tabla 7.
          span Función del ejercico fícico realizado
        .tabla-b.color-acento-contenido.tbl4.tbl-r
          table.mb-4
            caption Nota. UNED (2017)
            thead
              tr
                td Poco o ninguno ejercicio
                td Calorías diarias necesarias = TMB x 1,2
            tbody
              tr
                td Ejercicio ligero (1-3 días a la semana, ejercicios de baja intensidad).
                td Calorías diarias necesarias = TMB x 1,375
              tr
                td Ejercicio moderado (3-5 días a la semana, ejercicios de intensidad moderada).
                td Calorías diarias necesarias = TMB x 1,55
              tr
                td Ejercicio intenso (6-7 días a la semana, ejercicios de alta intensidad).
                td Calorías diarias necesarias = TMB x 1,725


        p.mb-5 Este concepto tiene que ver con la temperatura del medio ambiente, puesto que cuando una persona se encuentra a un ambiente a temperatura media de trópico, el metabolismo basal disminuye en un 10%, mientras que en climas con temperaturas altas el metabolismo basal puede bajar un 10% en relación con los lugares de clima frío.    
  
        .row
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Efecto térmico de los alimentos:
              
        p Este factor está representado por la cantidad de energía que utiliza el organismo para procesos como digestión, absorción, metabolismo y almacenamiento de los nutrientes que dan energía. Diariamente el organismo consume alrededor de un 10% de energía en los procesos antes mencionados.  

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Actividad física

    .row.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-9.mb-4
        p Este factor está representado por la energía que se gasta en el ejercicio físico voluntario y los movimientos que se realizan en las actividades diarias. Si se desarrolla alguna actividad física, las necesidades energéticas aumentan, en situaciones extremas puede alcanzar hasta cincuenta veces la consumida en reposo.        
        .row
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Actividades relacionadas con cada nivel de la actividad:

        .row.mb-3.pe-lg-3
          .col-auto.pe-2.mt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Actividad muy leve:</b>Actividades en posición sentada y de pie: pintar, manejar, trabajo de laboratorio, computación, coser, planchar, cocinar, jugar cartas y tocar un instrumento musical.
        .row.mb-3.pe-lg-3
          .col-auto.pe-2.mt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Actividad leve:</b>Caminar, trabajos eléctricos, trabajo en restaurante, limpieza de casa, cuidado de los niños, golf y tenis de mesa.                 
        .row.mb-3.pe-lg-3
          .col-auto.pe-2.mt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Actividad moderada:</b>Caminar vigorosamente, cortar el pasto, bailar, ciclismo en superficie plana, esquiar, tenis y llevar una carga.              
        .row.mb-3.pe-lg-3
          .col-auto.pe-2.mt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Actividad intensa:</b>Subir con carga por una pendiente, tala de árboles, excavación manual intensa, basquetbol, escalar, futbol, correr, natación, ciclismo con pendiente y aeróbicos. 
        .row.mb-3.pe-lg-3
          .col-auto.pe-2.mt-2
            img(src="@/assets/curso/temas/tema1/check.svg")
          .col.px-0
            p.mb-0 <b>Excepcional:</b>Atletas de alto rendimiento.                           
                  
      .col-lg-3.col-md-6.mb-3
        figure
          img(src='@/assets/curso/temas/tema3/img-7.png')   

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Gasto energético Total
       
    .row.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-3.col-md-6.mb-5
        figure
          img(src='@/assets/curso/temas/tema3/img-8.png') 

      .col-lg-7
        .cajon.color-secundario.p-4.mb-4.fnd-11
          p.mb-0 Es importante conocer el gasto energético diario para así saber lo que en realidad el cuerpo necesita, ya que a veces la dieta que se consume tiene un desequilibrio en nutrientes. Por ejemplo, cuando se consumen más calorías de las que se necesitan, el cuerpo las almacena en forma de grasa ocasionando un aumento de peso.

    .row.mb-4.pe-lg-3.align-items-center(data-aos="fade-left")
      .col-auto.pe-2
        figure
          img(src='@/assets/curso/temas/tema1/img-4.svg')
      .col-auto.px-0
        h3.mb-0 Método FAO, OMS y UNU
    p A continuación, se exponen las ecuaciones para calcular el gasto energético en reposo, elaboradas por expertos de la Organización de las Naciones Unidas para la Alimentación y la Agricultura, la Universidad de las Naciones Unidas y la Organización Mundial de la Salud:

    p.mb-5 Para calcular el gasto energético en reposo se puede utilizar el método de la Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO), la Organización Mundial de la Salud (OMS) y la Universidad de las Naciones Unidas (UNU): 1. Se calcula el gasto energético en reposo (GER) con las ecuaciones de la FAO,OMS y UNU. En esta ecuación se incluye el efecto térmico de los alimentos. 2. El gasto energético en reposo (GER) se multiplica por la constante del factor de actividad física.


    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in")
      .col-lg-8
        .n-box
          .contt
            p <b>Ejercicio como ejemplo: Cálculo del gasto energético total (GET)</b> 
            p Calcular el gasto energético total de una mujer de 30 años que mide 1.59 m, pesa 55 kg y cuyo índice de masa corporal (IMC) es de 20, lo cual se considera adecuado. Ella realiza actividad física leve, pues es profesora en una universidad y en las tardes camina durante 20 minutos para llegar a su casa.
          img.user(src="@/assets/curso/temas/tema3/img-9.png")

    .row.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-10
        .row
          .col-auto.mb-3
            h3.mb-0.fnd-2-1.fnd-2 Gasto energético en reposo (GER):
        p Para hallar el gasto energético en reposo de esta mujer de 30 años se debe tener en cuenta la Tabla 1 del modelo de la FAO, OMS y UNU donde:La ecuación para estimar el gasto energético en reposo para una mujer de 30 años es la siguiente:
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in")
      .col-lg-10
        .row.justify-content-center.align-items-center.fnd-12
          .col-lg-10.px-5.py-3
            .row.mb-4
              .col-auto.mb-3
                h3.mb-0.fnd-2-2.fnd-2 Ecuación gasto energético en reposo
            .row.lb-1.mb-4
              .col-auto
                h2 (GER)= 
              .col-auto
                p 14. 7 x P + 496 = 14.7 x 55 + 496 = 1304 kcal” (Iñarritu, s.f.). <br>(P = 55 kg).
            .row.mb-5
              p Para hallar el gasto energético en reposo por la actividad física que ella realiza se tiene en cuenta el valor para actividad física leve que está en la tabla 7:
              h4.mb-0 (GER) x factor de actividad física leve:
              p.mb-0 1304 x 1.5 = 1956 kcal
              p.mb-0 Gasto energético total (GET) = 1950
              p.mb-0 kcal/día” (Iñarritu, s.f.).




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
