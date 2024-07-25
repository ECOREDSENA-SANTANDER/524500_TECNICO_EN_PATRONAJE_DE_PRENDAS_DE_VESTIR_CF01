<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Ficha técnica de diseño (software de diseño)

    .row.mb-4
      .titulo-segundo.color-primario
        h2 2.1 Conceptos de dibujo plano
      p El dibujo plano es una técnica que emplea composiciones de formas bidimensionales para crear o esbozar el prototipo de un objeto deseado. Esta metodología se aplica en numerosos campos y es especialmente útil en la producción, ya que facilita la visualización de las ideas creativas y conceptuales durante el desarrollo funcional. 

    .row.mb-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Dibujo técnico - Dibujo bidimensional de prendas de vestir

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema2/tarjeta1/imagen1.png')          
        h3.text-center ¿Qué es el dibujo técnico? 
        p Conocido como el sistema que representa gráficamente uno o más objetos, con el fin de otorgar información útil para un posible y consecuente análisis que permitirá una próxima construcción o ejecución de un objeto.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema2/tarjeta1/imagen2.png')
        h3.text-center ¿Qué es el término bidimensional?
        p Es toda aquella figura que está compuesta por dos dimensiones, ancho y largo. El cuadrado, el triángulo, el rectángulo, el círculo, no tienen profundidad, son formas que cuando se trazan no involucran ningún tipo de volumen en su diseño.

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Tipos de línea

    .row.justify-content-center.align-items-center.mb-5    
      .col-10
        .titulo-sexto.color-secundario
          h5 Figura 1.
          span
            |  Tipos de línea.
        figure
          img(src='@/assets/curso/temas/tema2/imagen1.png')

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Canon de belleza – proporciones
      p Diferencias entre: figurín, ilustración, dibujo plano.

    TabsC.color-acento-botones
      .py-4.py-md-0(titulo="<strong>Figurín</strong>")
        .row.align-items-center(style='background-color: #FEF5E5')
          .col-md-4
            figure
              img.p-5(src='@/assets/curso/temas/tema2/tarjeta2/imagen1.png')
          .col-md-7
            h4 Figurín
            p Representar gráficamente el cuerpo y las prendas, con una expresión viva, un trazo fresco, un movimiento dinámico, una pose elegante y una expresión adecuada al tipo de vestimenta propuesto.
      .py-4.py-md-0(titulo="<strong>Ilustración</strong>")
        .row.align-items-center(style='background-color: #FEF5E5')
          .col-md-4
            figure
              img.p-5(src='@/assets/curso/temas/tema2/tarjeta2/imagen2.png')
          .col-md-7
            h4 Ilustración
            p Son dibujos, esquemas, bosquejos, bocetos o pinturas que se hacen relacionados a la moda, pueden ser de modelos, ropa o accesorios, prácticamente cualquier objeto o situación relacionada a la industria.
      .py-4.py-md-0(titulo="<strong>Dibujo Plano</strong>")
        .row.align-items-center(style='background-color: #FEF5E5')
          .col-md-4
            figure
              img.p-5(src='@/assets/curso/temas/tema2/tarjeta2/imagen3.png')
          .col-md-7
            h4 Dibujo Plano
            p Representación detallada de una prenda, es decir, se deben identificar todas las características técnicas de la prenda, pespuntes, botones, costuras, pinzas, acabados. No tiene movimiento y se debe identificar delantero y posterior.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Tipos de trazos - ejercicios de aprestamiento

    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema2/tarjeta3/imagen1.png' alt='AvatarTop')
        h2.text-center Posición de escritura
        p.text-center  Para hacer los ejercicios, trabaje siempre con el lápiz en posición de escritura.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema2/tarjeta3/imagen2.png' alt='AvatarTop')
        h2.text-center Horizontales 
        p.text-center Alternando de izquierda a derecha y de derecha a izquierda.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema2/tarjeta3/imagen3.png' alt='AvatarTop')
        h2.text-center Verticales
        p.text-center Alternando de arriba hacia abajo y de abajo hacia arriba.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema2/tarjeta3/imagen4.png' alt='AvatarTop')
        h2.text-center Diagonales
        p.text-center Alternando de izquierda a derecha y de derecha a izquierda.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema2/tarjeta3/imagen5.png' alt='AvatarTop')
        h2.text-center Círculos
        p.text-center Recuerde no apoyar la muñeca ni la mano.

    Separador

    .row
      #t_2_2.titulo-segundo.color-primario
        h2 2.2.  Categorización de prendas
      p En la segmentación de productos se implementa el término tipología, el cual sirve para categorizar de manera básica, “lógica” por tipo los productos, lo que se busca es identificar características similares que componen el producto y así ir categorizando para facilitar todo el proceso, desde la parte creativa hasta la parte operativa. 

    .row
      .col-md-12.p-5
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/imagen3.png')})`}"
           )
            h3.text-center.p-5 Qués es una tipología?
          .bloque-texto-g__texto.p-2
            p.text-center Es el estudio de los tipos o modelos que se usan para clasificar diversas cosas.

    .row.mb-0
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ División del cuerpo

    .row.justify-content-center.align-items-center.mb-5    
      .col-10
        .titulo-sexto.color-secundario
          h5 Figura 2.
          span
            | División del cuerpo
        figure
          img(src='@/assets/curso/temas/tema2/imagen4.png')
   
    .row.mb-0
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Bitácora de formas - Glosario técnico

    .row.mb-4
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-acento-contenido.p-5
          .tarjeta-numerada__numero
            .h2 1
          p.text-center 
            h3.text-center Pinzas
          p.text-center Pinza sencilla, doble pinza, pinza por sisa corte diagonal, pinza por escote.
          br
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-primario.p-5
          .tarjeta-numerada__numero
            .h2 2
          p.text-center 
            h3.text-center Cortes
          p.text-center Princesas, francés, corte horizontal y vertical, canesú con corte vertical.
          br
          br
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-acento-contenido.p-5
          .tarjeta-numerada__numero
            .h2 3
          p.text-center 
            h3.text-center Talles
          p.text-center Talle alto, talle medio, talle bajo. Cuellos - puños - bolsillos de parche - bolsillos de ribete - pantalón - largos - bolsillos - talles – detalles.

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img.p-4(src='@/assets/curso/temas/tema2/imagen12.png')
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3 Categoría de prendas - Tipologías – Bitácora de formas
                  p.mb-0 Revisa el contenido del video que puede resultar útil para complementar el aprendizaje acerca de la categorización de prendas.
                .col-sm-auto
                  a.boton.color-boton(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-file-download.text-sistm

    Separador

    .row.mt-4
      #t_2_3.titulo-segundo.color-primario
        h2 2.3.  Técnica de achurados y acabados

    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de  Técnica de achurados y acabados.

    Separador

    .row.mt-4
      #t_2_4.titulo-segundo.color-primario
        h2 2.4 Dibujo de bitácora de formas

    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Dibujo de bitácora de formas.

    Separador

    .row.mt-4
      #t_2_5.titulo-segundo.color-primario
        h2 2.5.  Dibujo plano de prendas

    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Dibujo plano de prendas.

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img.p-4(src='@/assets/curso/temas/tema2/imagen7.png')
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3 Dibujo plano para prendas
                  p.mb-0 Revisa el documento que pueden resultar útil para aprender más sobre la creación de dibujos planos para prendas.
                .col-sm-auto
                  a.boton.color-boton(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                    span.text-sistm Ir al sitio
                    i.fas.fa-file-download.text-sistm

    Separador

    .row.mt-4
      #t_2_6.titulo-segundo.color-primario
        h2 2.6.  Análisis de proporciones prendas superiores e inferiores

    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Análisis de proporciones prendas superiores e inferiores.
    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Análisis de proporciones prendas inferiores. 

    .row.mb-4.p-5
      .col-1
      .col-10
        .tarjeta.actividad.p-3.color-primario
          .row.justify-content-around.align-items-center      
            .col-1.justify-content-around.align-items-center
              figure
                img(src='@/assets/curso/temas/tema2/imagen8.png')
            .col-8.justify-content-around.align-items-center
              h3.mb-0 Análisis de Proporciones Prendas Superiores e Inferiores
              p.mb-0 Revisa el documento que pueden resultar útil para aprender más sobre el análisis de proporciones de prendas superiores e inferiores.
            .col-2.justify-content-around.align-items-center
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Descargar
                i.fas.fa-puzzle-piece
    
    Separador

    .row.mt-4
      #t_2_7.titulo-segundo.color-primario
        h2 2.7.  Interfaz programa CAD
      p Para el desarrollo de dibujos planos, se implementa software que permite agilizar y detallar de manera más certera un producto. Para el uso de los programas se hace necesario contar con la licencia que autoriza la implementación legal del mismo. El SENA cuenta con las licencias requeridas para el acceso del aprendiz sin ningún inconveniente. 

    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Interfaz programa CAD.

    Separador

    .row.mt-4
      #t_2_8.titulo-segundo.color-primario
        h2 2.8.  Ficha técnica
      p Son documentos en los cuales se describe de manera detallada la información técnica de un producto, por lo general se documenta la información operativa de cada uno de los procesos por los que pasa el producto, dichos documentos serán consultados de manera constante para validar que el proceso si corresponde al requerimiento. 

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/imagen10.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 <strong>¿Qué es ficha técnica?</strong>
          br
          br
          | Son documentos que contienen la información necesaria para la fabricación de un producto. dichos documentos serán consultados en los distintos procesos de producción. Los datos para incluir deben ser detallados.   

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Tipos de ficha técnica
      p Según el volumen, la cantidad, la rigurosidad de la producción y el cumplimiento de parámetros de calidad, se deciden los diferentes requerimientos técnicos que debe llevar la ficha técnica.


    .row.justify-content-center.align-items-center.mb-5    
      .col-10
        .titulo-sexto.color-secundario
          h5 Figura 3.
          span
            | Tipos de ficha técnica
        figure
          img(src='@/assets/curso/temas/tema2/imagen11.png')


    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
      .row(titulo="Especificaciones técnicas de diseño")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Dibujo plano.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Proporción.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Dimensión. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Lupas.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Acotaciones (cotas).
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema2/acordeon1/imagen1.png', alt='Imagen diseñando')
      .row(titulo="Especificaciones técnicas de patronaje")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Medidas bases: bases para la construcción de la moldería, dependiendo del requerimiento antropométrico (prendas inferiores o superiores)..
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Básico: moldería BASE de construcción, superiores o inferiores. Punto de partida para la construcción del plano.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Interpretación: modificaciones al patrón base para la correcta lectura del diseño o prenda a trabajar.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Señalización: convenciones o marcación para la correcta lectura del plano.    
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema2/acordeon1/imagen2.png', alt='Imagen trazando')
      .row(titulo="Especificaciones técnicas de escalado")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Despiece de moldería: juego de piezas para la construcción de una prenda o producto en una talla o modelo específico.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Proporciones: diferencia entre talla y talla para el incremento o disminución entre la talla base y los requerimientos de producción.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Nido de escalado: malla o nido de la diferencia entre talla y talla del trazo o plano. 
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema2/acordeon1/imagen3.png', alt='Imagen colocando un parámetro para coser')
      .row(titulo="Especificaciones técnicas de trazo y corte")
        .col-md-6.mb-4.mb-md-0
          p Para realizar el corte de una prenda o producto es necesario identificar por talla, referencia, material, color y demás instrucciones de corte.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Cantidad de corte por talla.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Cantidad de corte por pieza.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Referencia por color.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema2/acordeon1/imagen4.png', alt='Imagen midiendo con un cartabon una prenda de vestir')

    .row.mt-5(style='background-color: #D1BCFF')
      .col-1
      .col-3.p-5 
        img(src='@/assets/curso/temas/tema1/signo-de-interrogacion.png')
      .col-7.p-5
        br
        p <strong>Socialización de formatos</strong>  <br>
        p <strong>Nota:</strong>  todo el texto tiene imágenes visuales de ref., las cuales complementan la información entregada - Anexar imágenes ppt de referencia..  

</template>

<script>
export default {
  name: 'Tema2',
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
