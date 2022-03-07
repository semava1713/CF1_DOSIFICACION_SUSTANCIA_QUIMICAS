<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.text-white 3
      h1 Estudios Ambientales

    separador
</template>
<script>
export default {
  name: 'Tema3',
  components: {},
  data: () => ({
    indicadorImagenZoom: true,
    datosSlyder: [
      {
        texto:
          '<b>Alcance del proyecto, obra o actividad: </b> incluye la planeación,  el emplazamiento,  la instalación y la construcción, por otro lado, se debe tener en cuenta también el montaje, la operación,  el mantenimiento, el desmantelamiento y abandono y/o terminación de todas las acciones, en adición los usos del espacio, actividades e infraestructura relacionados y asociados con su desarrollo.',
        imagen: require('@/assets/curso/tema3/img08.png'),
      },
      {
        texto:
          '<b>Ambiente: </b> fracción del globo terráqueo que comprende los elementos naturales, tanto físicos como biológicos, adicionalmente se deben tener en cuenta los siguientes puntos: elementos artificiales, sociales y culturales, y las interacciones de estos entre sí.',
        imagen: require('@/assets/curso/tema3/img09.png'),
      },
      {
        texto:
          '<b>Área de estudio: </b>superficie de contexto general, continua o discontinua, en la que se manifestarían los <b>impactos ambientales significativos</b> que potencialmente generarían las alternativas, técnica y ambientalmente racionales y que se contemplen para la ejecución de un proyecto, obra o actividad en el marco de un diagnóstico ambiental de alternativas.',
        imagen: require('@/assets/curso/tema3/img10.png'),
      },
      {
        texto:
          '<b>Área de influencia: </b>zona en la cual se manifiestan de manera objetiva y en lo posible cuantificable, los <b>impactos ambientales significativos</b> ocasionados por la ejecución de un proyecto, obra o actividad, sobre los medios abiótico, biótico y socioeconómico, en cada uno de los componentes de dichos medios. Por otro lado, debido a que las áreas de los impactos pueden variar dependiendo del componente que se analice, el área de influencia podrá corresponder a varios polígonos distintos que se entrecrucen entre sí.',
        imagen: require('@/assets/curso/tema3/img11.png'),
      },
      {
        texto:
          '<b>Componente: </b>unidad conceptual que agrupa factores ambientales y que a su vez constituye uno de los elementos que conforman un medio (abiótico, biótico o socioeconómico); por ejemplo, los componentes geológico, hidrológico, hidrogeológico, oceanográfico, geotécnico y atmosférico,  que hacen parte del medio abiótico.',
        imagen: require('@/assets/curso/tema3/img12.svg'),
      },
      {
        texto:
          '<b>Dinámica poblacional: </b>cambios y proyección de población en un territorio.',
        imagen: require('@/assets/curso/tema3/img13.png'),
      },
      {
        texto:
          '<b>Ecosistema: </b>complejo dinámico de comunidades vegetales, animales y microorganismos y su medio no viviente que interactúan como una unidad funcional.',
        imagen: require('@/assets/curso/tema3/img14.png'),
      },
      {
        texto:
          '<b>Factor ambiental: </b>atributo de un componente ambiental que puede ser descrito mediante parámetros ambientales.',
        imagen: require('@/assets/curso/tema3/img15.svg'),
      },
      {
        texto:
          '<b>Impacto ambiental: </b>cualquier alteración en el medio ambiental biótico, abiótico y socioeconómico, que sea adverso o beneficioso, total o parcial y que pueda ser atribuido al desarrollo de un proyecto, obra o actividad.',
        imagen: require('@/assets/curso/tema3/img16.png'),
      },
      {
        texto:
          '<b>Parámetro ambiental: </b>valor que caracteriza alguna propiedad de un proceso o fenómeno que ocurre en el ambiente, por ejemplo: pH del agua o del suelo, conductividad eléctrica o la temperatura.',
        imagen: require('@/assets/curso/tema3/img17.png'),
      },
      {
        texto:
          '<b>Zonificación ambiental: </b>proceso de sectorización de un área compleja en áreas relativamente homogéneas, de acuerdo con las características y la sensibilidad ambiental de los componentes de los medios abiótico, biótico y socioeconómico.',
        imagen: require('@/assets/curso/tema3/img18.png'),
      },
    ],
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
