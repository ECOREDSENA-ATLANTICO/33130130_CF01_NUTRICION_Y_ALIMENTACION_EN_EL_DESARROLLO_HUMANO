<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    #Actividad                
      <Actividad :cuestionario="cuestionario" />

</template>

<script>
import Actividad from '@/components/actividad/Actividad'
export default {
  name: 'ActividadDidactica',
  components: { Actividad },
  data: () => ({
    cuestionario: {
      tema:
        'Principales componentes de los alimentos: su rol en el gasto energético y la fisiología humana.',
      titulo: 'Cuestionario',
      introduccion:
        'Lea la afirmación de cada ítem y luego señale verdadero o falso según corresponda.',
      barajarPreguntas: false,
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál de los siguientes macronutrientes es la principal fuente de energía para el cuerpo?',
          imagen: require('@/assets/actividad/img-1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Proteínas.', esCorrecta: false },
            { id: 'b', texto: 'Carbohidratos.', esCorrecta: true },
            { id: 'c', texto: 'Vitaminas.', esCorrecta: false },
            { id: 'd', texto: 'Minerales.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Qué tipo de grasa se considera más saludable y beneficiosa para el corazón?',
          imagen: require('@/assets/actividad/img-2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Grasas saturadas.', esCorrecta: false },
            { id: 'b', texto: 'Grasas trans.', esCorrecta: false },
            { id: 'c', texto: 'Grasas monoinsaturadas.', esCorrecta: true },
            { id: 'd', texto: 'Grasas poliinsaturadas.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Cuál de las siguientes vitaminas es esencial para la coagulación de la sangre?',
          imagen: require('@/assets/actividad/img-3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Vitamina A.', esCorrecta: false },
            { id: 'b', texto: 'Vitamina K.', esCorrecta: true },
            { id: 'c', texto: 'Vitamina C.', esCorrecta: false },
            { id: 'd', texto: 'Vitamina D.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué componente de los alimentos ayuda a construir y reparar tejidos en el cuerpo?',
          imagen: require('@/assets/actividad/img-4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Carbohidratos.', esCorrecta: false },
            { id: 'b', texto: 'Grasas.', esCorrecta: false },
            { id: 'c', texto: 'Proteínas.', esCorrecta: true },
            { id: 'd', texto: 'Azucares.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Cuál es la función principal de las fibras dietéticas en la alimentación?',
          imagen: require('@/assets/actividad/img-5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Proveer energía.', esCorrecta: false },
            {
              id: 'b',
              texto: 'Regular el tránsito intestinal.',
              esCorrecta: true,
            },
            { id: 'c', texto: 'Construir músculo.', esCorrecta: false },
            { id: 'd', texto: 'Mejorar la visión.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué mineral es crucial para el transporte de oxígeno en la sangre?',
          imagen: require('@/assets/actividad/img-1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Calcio.', esCorrecta: false },
            { id: 'b', texto: 'Hierro.', esCorrecta: true },
            { id: 'c', texto: 'Potasio.', esCorrecta: false },
            { id: 'd', texto: 'Magnesio.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Cuál de las siguientes opciones describe mejor el papel de los lípidos en la dieta?',
          imagen: require('@/assets/actividad/img-2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Son la única fuente de energía.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Aportan nutrientes y ayudan a absorber vitaminas liposolubles.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'No tienen valor energético.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Solo se encuentran en alimentos de origen animal.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué tipo de carbohidratos se digieren más lentamente y son beneficiosos para la salud?',
          imagen: require('@/assets/actividad/img-3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Carbohidratos simples.', esCorrecta: false },
            { id: 'b', texto: 'Carbohidratos complejos.', esCorrecta: true },
            { id: 'c', texto: 'Azúcares añadidos.', esCorrecta: false },
            { id: 'd', texto: 'Almidones refinados.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: '¿Qué vitamina es conocida por su papel en la salud ósea?',
          imagen: require('@/assets/actividad/img-4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Vitamina B12.', esCorrecta: false },
            { id: 'b', texto: 'Vitamina C.', esCorrecta: false },
            { id: 'c', texto: 'Vitamina D.', esCorrecta: true },
            { id: 'd', texto: 'Vitamina E.', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto: '¿Qué es el metabolismo?',
          imagen: require('@/assets/actividad/img-5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El proceso de absorción de nutrientes.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La suma de todas las reacciones químicas en el cuerpo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'La eliminación de desechos del cuerpo.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La conversión de alimentos en agua y dióxido de carbono.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado:
        '¡Excelente! Te felicito, has superado la actividad.',
      mensaje_final_reprobado:
        'Te recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
  computed: {},
  methods: {},
}
</script>
