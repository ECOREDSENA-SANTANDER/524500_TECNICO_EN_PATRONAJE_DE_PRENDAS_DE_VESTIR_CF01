<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row
      //.cajon.color-primario.p-4.mb-0
      .row
        .col-9
          .cajon.color-primario.p-4.mb-0
            p.mb-2(style='font-size: 18px') El patronista constituye un importante punto de conexión entre el diseño y el proceso de fabricación de las prendas de vestir; dentro de su quehacer se identifican diferentes labores, además debe contar con los conocimientos propios del área, entre los cuales se encuentra, la información específica y el lenguaje técnico que se emplea en el diseño de modas, con el fin de establecer una comunicación efectiva con el área creativa (diseñador) que le permita la comprensión y ejecución de los proyectos.   
          br
          p.mb-2(style='font-size: 16px') A continuación, conocerá los conceptos y terminología empleados en el diseño de prendas de vestir, los cuales le permitirán lograr un acercamiento e inmersión en el mundo de la moda. A lo largo de la historia han surgido cambios significativos en la industria, los cuales han permitido la segmentación y categorización de los productos a través de tipos, usos, precio y necesidad. Hoy por hoy, la gran mayoría de la industria desarrolla diferentes investigaciones que le permiten predecir los comportamientos futuros del mercado y establecer tendencias, proyectando así colores, formas, textiles, insumos, materiales, grafías y demás elementos que componen una prenda; en este sentido, se hace necesario identificar cada uno de estos elementos, con el fin de llevar a cabo la producción y elaboración de prendas de vestir a grande, mediana y pequeña escala.    
        .col-3.align-items-center
          br
          br
          img(src='@/assets/curso/temas/introduccion/introduccion.png', alt='Dama en un taller')
    
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
