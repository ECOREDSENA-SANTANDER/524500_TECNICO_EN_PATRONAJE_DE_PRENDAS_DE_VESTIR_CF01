<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Fundamentación Textil

    .row.mb-4
      .titulo-segundo.color-primario
        h2 3.1 Clasificación y conceptualización de las fibras naturales, químicas (artificiales y sintéticas)
      p Las fibras son una composición de filamentos que al entrelazarse componen los hilos, los hilos son el punto de partida para la producción de un textil; la composición unitaria de una materia sólida con cualquier estructura compone una fibra.
 
    .row.bm-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Proceso productivo textil

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 <strong>Fibras - Hilos - Tejidos - Telas - Acabados - Confección</strong>
        <br> <br>
        p.mb-0 <strong>¿Qué es una fibra?</strong>
        <br> <br>
        p Materia sólida unitaria de cualquier estructura textil.Fibra es cada uno de los filamentos que componen las unidades fundamentales en la fabricación de hilos, textiles y telas.
        <br> <br>
        p Filamentos: término utilizado para identificar fibras de longitud indeterminada.   

    .row.bm-5.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Clasificación de las fibras textiles

    .row.mb-5.align-items-center.justify-content-center
      .col-lg-9
        .row
          .col-3.position-relative
            .avatar
              img(src="@/assets/curso/temas/tema3/imagen16.svg")
          .col-9.p-5(style='background-color: #FEF5E5')
            .row
              .col-1
              .col-10
                p Se pueden clasificar de acuerdo con su:
                ul.lista-ul--color.vmorada.fa-ul
                  li.mb-0
                    i.lista-ul__vineta
                    span.mb-0 Origen
                  li.mb-0
                    i.lista-ul__vineta
                    span.mb-0 Composición
                p Esto nos permite identificar los procesos a los que son sometidas las fibras para la conformación de los productos textiles.


    .row.bm-5.mt-5
      h3(style="color: #673AB7") Naturales: 
      p Son fibras que se extraen de los animales o de origen vegetal, se caracterizan por ser fragmentos, hebras o pelo y que pueden hilarse para dar lugar a hilos o cuerdas.


    TabsA.color-acento-botones
      .tarjeta.color-acento-botones.p-4(titulo="Fibras animales" style='background-color: #FEF5E5')
        .row
          p Las fibras de origen animal son de lana, pelo y secreciones, como la seda, folículos pilosos.
        .row
          .col-3
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Oveja.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Alpaca.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Vicuña.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Camello.
          .col-3
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Cabra cachemira.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Mohair.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Pelo de yak.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Conejo angora
      .tarjeta.color-acento-botones.p-4(titulo="Fibras vegetales" style='background-color: #FEF5E5')
        .row
          p Entre las fibras de origen vegetal están las que se extraen:
        .row
          .col-2
            p <strong>De la semilla</strong>
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Algodón
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Ceiba o Kapok
          .col-2
            p <strong>Del tallo</strong>
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Lino.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Yute.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Bambú.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Cáñamo.
          .col-2
            p <strong>De la hoja</strong>
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Abacá.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Cabuya.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Esparto.
          .col-2
            p <strong>De fruto</strong>
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Bonote (Coco)
          .col-2
            p <strong>De la raíz</strong>
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Zacatón
      .tarjeta.color-acento-botones.p-4(titulo="Fibras minerales" style='background-color: #FEF5E5')
        .row
          p Las fibras de origen mineral se obtienen de minerales de estructura fibrosa.
        .row
          .col-3
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Lana de roca.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Amianto.
          .col-3
            ul.lista-ul--color.vmorada.fa-ul
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Fibra cerámica.
              li.mb-0
                i.lista-ul__vineta.color-primario
                | Fibra asbesto.

    .row.mb-5.mt-5
      h3(style="color: #673AB7") Químicas o intervenidas por el hombre
      p Las fibras que no se encuentran en la naturaleza como tales, deben ser manufacturadas por el hombre a través de procesos químicos. Se clasifican a su vez en: fibras artificiales y fibras sintéticas.

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema3/tarjeta1/imagen1.png')          
        h3.text-center Fibras artificiales
        p Son aquellas obtenidas a partir de fibras naturales, mediante un proceso químico de transformación; se logra transformar los polímeros naturales utilizados como materia prima en nuevas fibras artificiales con características propias y aplicaciones específicas.
        ul.lista-ul
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Rayón o seda artificial.
          li.mb-0
            i.lista-ul__vineta.color-color-acento-botones
            | Fibra de vidrio.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema3/tarjeta1/imagen2.png')
        h3.text-center Fibras sintéticas
        p Fibras textiles que provienen de productos derivados del petróleo / polímeros sintéticos, son enteramente químicas; tanto la síntesis de la materia prima como la fabricación del filamento.
        ul.lista-ul
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Fibras de poliamida o nailon.
          li.mb-0
            i.lista-ul__vineta.color-color-acento-botones
            | Nailon 6 y nylon 6-6.
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Aramidas.
          li.mb-0
            i.lista-ul__vineta.color-color-acento-botones
            | Elástano o spandex.
      
    .row
      .col-3
      .col-md-4
        h3(style="color: #673AB7") Inteligentes o técnicos
    .row
      .col-3
      .col-md-6.p-3(style="background-color: #DADDDF")
        p Pasivos, activos, de memora, ultrainteligentes, microcápsulas, nanotecnología.
    .row.mt-4
      .col-3
      .col-md-4
        h3(style="color: #673AB7") Renovables o sostenibles
    .row.mb-5
      .col-3
      .col-md-6.p-3(style="background-color: #DADDDF")
        p Pet reciclado, algodón orgánico, cuero vegetal, nylon regenerado, algas marinas.

    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .tarjeta(style='background-color: #673AB7')
          .row.justify-content-center.align-items-center
            .col-1.col-md-1.d-none.d-lg-block
              img.mr-3.mt-mb-3(src="@/assets/curso/temas/tema3/tela.png")
            .col-sm-12.col-md-10.col-lg-10
              .row.justify-content-center.align-items-center
                .col-sm-10.col-md-10.col-lg-10.mb-3.mb-sm-0
                  h3.mt-3.text-white Clasificación de las fibras textiles
                  p.mb-3.text-white Revisa el documento que pueden resultar útil para aprender más sobre la clasificación de las fibras textiles.
                .col-sm-2-col-md-2.col-lg-2
                  a.boton.color-boton(href="https://youtu.be/zjp1OL2DCug" target="_blank")
                    span.texto-negro Ir al sitio
                    i.fas.fa-file-download

    Separador

    .row.mb-4
      #t_3_2.titulo-segundo.color-primario
        h2 3.2. Identificación fibras por combustión
      p Conocer la composición de una fibra es la base de su utilidad, con la composición se logra identificar su comportamiento al ser manipuladas y permite garantizar la idoneidad en la elección frente a la función del diseño y del uso para el que están destinadas. La combustión es el proceso más común para la identificación de cada componente.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/imagen3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 <strong>¿Para qué?</strong>
          br
          br
          | Los materiales textiles son los cimientos de la moda y elegir los adecuados es la clave de un proyecto con éxito. Conocer su composición es muy útil para prever su comportamiento cuando se manipulan y para garantizar la idoneidad de su elección en función del diseño y del uso para el que están destinados.

    .row.mt-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Procedimiento
      p El procedimiento para identificar las fibras que componen una determinada tela depende de la naturaleza de la muestra, de la experiencia del analista y del equipo disponible. Para determinar de forma exacta su composición se deberán combinar varias pruebas de identificación. Una de las más sencillas es la prueba de identificación mediante el análisis por combustión.
    
    .row.justify-content-center.align-items-center.mb-5.mt-5(style='background-color: #D1BCFF')
      .col-2.col-md-2.col-lg-2
        img(src='@/assets/curso/temas/tema1/signo-de-interrogacion.png')
      .col-sm-12.col-md-7.col-lg-7.p-5
        p.mb-2 <strong>Análisis pirognóstico </strong>
        p.mb-2 Definición etimológica: <strong>piro:</strong> fuego, <strong>gnosis:</strong> conocimiento.  
        p.mb-2 Es un método muy simple que nos dará información sobre la naturaleza de las fibras que componen la tela con la que se está trabajando. Llamada también prueba de combustión.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Prueba de combustión
      p Esta prueba consiste en exponer a una llama, fibras o hilos de la materia textil que queremos identificar, analizando su forma de:    
    
    .row.justify-content-center.align-items-center.mb-5.mt-3
      .col-lg-11
        .row.align-items-center.justify-content-center
          .col-xl-4
            .row
              .col-1.position-relative
                .avatar
                  img.mb-1(src="@/assets/curso/temas/tema3/avatar1/imagen1.png")
              .col-11
                .row.p-md-4.borde-redondo.borde-morado100
                  h4.text-center.mt-2 <strong>Arder</strong>
          .col-xl-4
            .row
              .col-1.position-relative
                .avatar
                  img.mb-1(src="@/assets/curso/temas/tema3/avatar1/imagen2.png")
              .col-11
                .row.p-md-4.borde-redondo.borde-morado100
                  h4.text-center.mt-2 <strong>El olor desprendido</strong>
          .col-xl-4
            .row
              .col-1.position-relative
                .avatar
                  img.mb-1(src="@/assets/curso/temas/tema3/avatar1/imagen3.png")
              .col-11
                .row.p-md-4.borde-redondo.borde-morado100
                  h4.text-center.mb-0.mt-0 <strong>El residuo que produce la combustión</strong>

    .row.mt-4.mb-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Materiales, equipos y útiles de trabajo

    .row.mb-5.align-items-center.justify-content-center
      .col-lg-10
        .row
          .col-3.position-relative
            .avatar
              img.mt-5(src="@/assets/curso/temas/tema3/imagen15.png")
          .col-9.ps-5(style='background-color: #FEF5E5')
            .row
              .col-1
              .col-8
                ul.lista-ul--color.vmorada.fa-ul.mt-2
                  li.mb-0
                    i.lista-ul__vineta.mb-0
                    span.mb-0 Muestras textiles 5 cm x 5 cm.
                  li.mb-0
                    i.lista-ul__vineta
                    span.mb-0 Mechero o veladora.
                  li.mb-0
                    i.lista-ul__vineta
                    | Cenicero.
                  li.mb-0
                    i.lista-ul__vineta
                    | Papel aluminio.
                  li.mb-0
                    i.lista-ul__vineta
                    | Pinzas.
                  li.mb-0
                    i.lista-ul__vineta
                    | Tijeras.

    .row.mt-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Normas específicas de trabajo y seguridad

    .row.align-items-center.justify-content-center
      .col-xl-12
        .row
          .col-1.position-relative
            .avatar.p-4
              img(src="@/assets/curso/temas/tema3/avatar2/imagen1.png")
          .col-11
            .row.p-md-5.borde-redondo(style='background-color: #D1BCFF')
              h3 Uso del mechero o veladora
              p Antes de encender el mechero o veladora, comprobar que no hay material inflamable a su alrededor. Para apagar el mechero o veladora, humedezca con un poco de agua, nunca soplar.

    .row.align-items-center.justify-content-center.mb-5.mt-3
      .col-xl-12
        .row
          .col-1.position-relative
            .avatar.p-4
              img(src="@/assets/curso/temas/tema3/avatar2/imagen2.png")
          .col-11
            .row.p-md-5.borde-redondo(style='background-color: #673AB7')
              h3.text-white Quemaduras
              p.text-white Prestar especial atención cuando se trabaje con muestras de tejidos compuestos por fibras que arden fundiéndose. Si se producen pequeñas quemaduras, estas se tratarán lavando la zona afectada con agua fría.

    .row.mt-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Procedimiento experimental
    
    .tarjeta.tarjeta--color.p-4(style="background-color: #E8E4FF")
      PasosB.color-primario
        .row(titulo="Paso1")
          .col-md-6.mb-4.mb-md-0
            ul.lista-ul--color.vmorada.fa-ul.p-5
              li
                i.lista-ul__vineta.mb-0
                | Deshilachar y extraer varios hilos del tejido.
              li
                i.lista-ul__vineta.mb-0
                | Verificar si aparentemente hay diferencias entre ellos con respecto al brillo, a la torsión o al color.
              li
                i.lista-ul__vineta.mb-0
                | Separar los hilos, si hay diferencias evidentes entre ellos, esto indica que puede haber dos o más fibras en la muestra.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema3/paso1/imagen1.svg', alt='Manos y tejido')
        .row(titulo="Paso2")
          .col-md-6.mb-4.mb-md-0
            ul.lista-ul--color.vmorada.fa-ul.p-5
              li
                i.lista-ul__vineta.mb-0
                | Sostener los hilos en forma horizontal con ayuda de una pinza.
              li
                i.lista-ul__vineta.mb-0
                | Acercar los hilos lentamente al borde de la llama y observar su comportamiento.
              li
                i.lista-ul__vineta.mb-0
                | Comprobar si se enroscan, si se encogen o si se alejan de la llama.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema3/paso1/imagen1.svg', alt='Manos encendiendo un aromatizante')
        .row(titulo="Paso3")
          .col-md-6.mb-4.mb-md-0
            ul.lista-ul--color.vmorada.fa-ul.p-5
              li
                i.lista-ul__vineta.mb-0
                | Introducir el extremo de la muestra en la llama y observar su comportamiento.
              li
                i.lista-ul__vineta.mb-0
                | Comprobar si se funde o si arde y si lo hace lentamente o con dificultad.
              li
                i.lista-ul__vineta.mb-0
                | Analizar la llama que se produce durante la combustión.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema3/paso1/imagen3.svg', alt='Manos con un fósforo encendido')
        .row(titulo="Paso4")
          .col-md-6.mb-4.mb-md-0
            ul.lista-ul--color.vmorada.fa-ul.p-5
              li
                i.lista-ul__vineta.mb-0
                | Retirar la muestra de la llama y observar su comportamiento. Comprobar si continúa ardiendo con o sin fusión y si se autoextingue.
              li
                i.lista-ul__vineta.mb-0
                | Analizar el humo que se desprende durante la combustión, determinando su color.
              li
                i.lista-ul__vineta.mb-0
                | Analizar el olor que se desprende durante la combustión. Comprobar si el olor es a papel quemado, a pelo quemado, a vinagre, a apio cocido, a cera fundida, dulzón, aromático o desagradable.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema3/paso1/imagen4.png', alt='Humo')
        .row(titulo="Paso5")
          .col-md-6.mb-4.mb-md-0
            ul.lista-ul--color.vmorada.fa-ul.p-5
              li
                i.lista-ul__vineta.mb-0
                | Cuando la muestra esté fría, examinar las características de los residuos. 
              li
                i.lista-ul__vineta.mb-0
                | Comprobar la cantidad de ceniza y su forma, determinar también si es blanda, dura o quebradiza.
              li
                i.lista-ul__vineta.mb-0
                | Repetir el proceso para verificar los resultados obtenidos.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema3/paso1/imagen5.png', alt='Residuos de ceniza')

    Separador
    
    .row.mt-5
      #t_3_3.titulo-segundo.color-primario
        h2 3.3.  Clasificación de los hilos
      p Los hilos son un conjunto de fibras textiles que son sometidas a un proceso de torsión, el cual permite que se genere un recorrido de gran longitud. Dentro de su clasificación se identifican elementos como los tipos de torsiones, titulación o numeración; la lectura de esta información es lo que permite determinar la idoneidad al momento de seleccionar los insumos para la elaboración de una prenda.

    
    
    .row.justify-content-center.align-items-center.mb-5(style='background-color: #FEF5E5')
      .col-3.col-md-3.col-lg-3
        img.mt-3.mb-3(src='@/assets/curso/temas/tema3/imagen4.svg')          
      .col-sm-12.col-md-7.col-lg-7
        p <strong>La hilatura</strong>
        p Consiste en elaborar o fabricar el hilo a partir de una mecha o cinta, puede realizarse en una variedad de máquinas que estira y confiere cohesión a la masa de fibras, obteniéndose el hilo.
        .row
          .col-5
            p.mb-2 <strong>Hilatura manual Procedimiento de hilatura</strong> 
            p <strong>Hilatura mecánica Procedimiento de hilatura</strong>
          .col-1
            h3.texto-morado100.mb-4 >
            h3.texto-morado100 >
          .col-5
            p.mb-2 Con el huso - La rueca - Bergadana - El spinning Jenny.
            p La mule - Jenny - Selfactina - Continuas de hilar - Máquinas más modernas.
    
    .row.mb-4.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Los hilos
      p.mb-4 Los hilos tienen un papel muy importante en la determinación del tacto y el comportamiento de la tela, pueden forzar el buen comportamiento de la fibra o compensar algunas propiedades deficientes. La efectividad de un acabado depende de la selección adecuada del hilo.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/imagen6.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 <strong>¿Qué es un hilo?</strong>
          br
          br
          | Producto de longitud sustancial y corte seccional, relativamente pequeño, consistente de fibras o filamentos, con o sin torsión, es decir, un hilo es una hebra larga y delgada, elaborada con fibras de material textil. Un hilo está compuesto por 1,2 o más cabos torcidos entre sí.

    .row.mb-2.mt-3
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ La torsión 
      p Se entiende por torsiones a la acción que sufre un conjunto de fibras, al proporcionarles cierta cantidad de giros en sentido de su eje longitudinal, y como consecuencia, la porción de fibras adquiere una cohesión y consistencia, provocando así mayor resistencia.
      p La cantidad de torsión de los hilos puede tener otras finalidades tales como: provocar determinados efectos en el teñido, producir reflejos en el tejido, flexibilidad o rigidez.

    .row.mb-5.mt-5
      .col-lg-10.position-relative
        .row
          .col-3
            .avatar
              img(src="@/assets/curso/temas/tema3/imagen7.svg", alt="alt")
        .row
          .col-9.ps-5(style='background-color: #D1BCFF')
              ul.lista-ul--color.vmorada.fa-ul.mt-5.mb-5
                li.mb-0 
                  i.lista-ul__vineta.mb-0
                  span.mb-0 <strong>Resistencia:</strong> A mayor torsión, mayor resistencia.
                li.mb-0
                  i.lista-ul__vineta.mb-0
                  span.mb-0 <strong>Elasticidad:</strong> A mayor torsión, mayor elasticidad.
                li.mb-0
                  i.lista-ul__vineta.mb-0
                  span.mb-0 <strong>Aspecto:</strong> A mayor torsión menor diámetro aparente del hilo (por la mayor compacidad).
                li.mb-0 
                  i.lista-ul__vineta.mb-0
                  span.mb-0 <strong>Tacto del tejido:</strong> Una torsión ligera proporciona telas de superficie suave, mientras que los hilos muy torcidos producen tejidos de superficie dura.
                li.mb-0
                  i.lista-ul__vineta.mb-0
                  span.mb-0 <strong>Arrugabilidad del tejido:</strong> A mayor torsión en el hilo, menor propensión de la tela a arrugarse.
                li.mb-0
                  i.lista-ul__vineta.mb-0
                  span.mb-0 <strong>Contracción:</strong> Los hilos elaborados muy torcidos encogen mucho más.

    .row.mb-4.mt-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Tipos de torsión
      p El tipo de torsión la define el sentido de rotación del huso al momento en que se está hilando, existiendo dos tipos:

    .row.justify-content-center.align-items-center.mb-5.mt-4
      .col-10
        .row.justify-content-center.align-items-center
          .col-md-5.col-xl.mb-4.mb-xl-0
            .tarjeta-numerada.color-primario.p-5.borde-morado100
              .tarjeta-numerada__numero.estilo500
                .h2.texto-morado100 Z
              p.text-center 
                h3 La torsión “Z” (derecha)
              p El huso en donde se está hilando gira en sentido a las manecillas del reloj.
          .col-md-5.col-xl.mb-4.mb-xl-0
            .tarjeta-numerada.color-primario.p-5.borde-morado100
              .tarjeta-numerada__numero.estilo500
                .h2.texto-morado100 S
              p.text-center 
                h3 La torsión “S” (izquierda)
              p El huso donde se está hilando gira en sentido contrario a las manecillas del reloj.

    .row.mb-4
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Clasificación de los hilos

    .tarjeta--container.row
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta2/imagen1.png')          
        h2.text-center Hilados (spun)
        .row
          .col-3
            p.mb-5 <strong>Sencillos</strong>
            br
            p <strong>Doblados</strong>
          .col-7
            ul.lista-ul
              li.mb-0
                i.lista-ul__vineta.color-acento-botones
                | Cardados
              li.mb-0
                i.lista-ul__vineta.color-color-acento-botones
                | Peinados
              li.mb-3
                i.lista-ul__vineta.color-color-acento-botones
                | Con efecto
              li.mb-0
                i.lista-ul__vineta.color-acento-botones
                | Con torsión
              li.mb-0
                i.lista-ul__vineta.color-color-acento-botones
                | Retorcidos
              li.mb-0
                i.lista-ul__vineta.color-acento-botones
                | Cableados
              li.mb-0
                i.lista-ul__vineta.color-color-acento-botones
                | Sin torsión  
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta2/imagen2.png')
        h2.text-center Filamentos
        p Fibras textiles que provienen de productos derivados del petróleo / polímeros sintéticos, son enteramente químicas; tanto la síntesis de la materia prima como la fabricación del filamento.
        ul.lista-ul
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Monofilamentos, multifilamentos.
          li.mb-0
            i.lista-ul__vineta.color-color-acento-botones
            | Lisos, texturizados.
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Con o sin torsión.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta2/imagen3.png')
        h2.text-center Otros
        p Fibras textiles que provienen de productos derivados del petróleo / polímeros sintéticos, son enteramente químicas; tanto la síntesis de la materia prima como la fabricación del filamento.
        ul.lista-ul
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Trenzados.
          li.mb-0
            i.lista-ul__vineta.color-color-acento-botones
            | Coreply - corespun.
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Fantasía.
          li.mb-0
            i.lista-ul__vineta.color-acento-botones
            | Teñidos.

    .row.mb-5.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Caracterización - Título o numeración
              
    .row.mb-5.mt-5.align-items-center.justify-content-center
      .col-lg-10
        .row
          .col-1.position-relative
            .avatar
              img(src="@/assets/curso/temas/tema3/signo-de-interrogacion.png")
          .col-11.borde-redondo.p-5(style='background-color: #D1BCFF')
            .row
              .col-1
              .col-9
                p Método para expresar la longitud específica o la longitud por unidad de masa de un hilo.

    .row.mb-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Numeración

    .row.mb-5.align-items-center.justify-content-center
      .col-lg-10
        .row
          .col-3.position-relative
            .avatar
              img(src="@/assets/curso/temas/tema3/imagen8.png")
          .col-9.ps-5.mt-3(style='background-color: #FEF5E5')
            .row
              .col-11.ps-5
                p.mt-4 Los números que describen las características de un hilo se llaman título, y deben ir precedidos del símbolo del sistema que se haya empleado. El título propiamente dicho es la relación que existe entre la longitud y el peso.
                p Los sistemas de numeración se clasifican en dos grupos:
                ul.lista-ul--color.vmorada.fa-ul
                  li.mb-0
                    i.lista-ul__vineta.color-acento-botones
                    | <strong>Sistemas directos</strong>
                  li.mb-0
                    i.lista-ul__vineta.color-color-acento-botones
                    | <strong>Sistemas indirectos</strong>

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Sistemas de numeración

    TabsC.color-acento-botones
      .py-4.py-md-0(titulo="<strong>Sistemas directos</strong>")
        .row(style='background-color: #FEF5E5')
          .col-6.p-5
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta3/imagen1.png')
          .col-md-6.p-5
            p (Longitud constante y peso variable) Cuanto más elevado es el número, más grueso es el hilado o fibra.
            p <strong>Tex:</strong> peso en gramos de 1.000 metros de hilo. 
            p <strong>- 1Tex = 10D Tex - Decitex (D Tex):</strong> es el peso en gramos de 10.000 metros de hilado. 
            p <strong>- 1 DTex = 0.9 Den - Denier (Den):</strong> es el peso en gramos de 9000 metros de hilado o fibra.
            p Esta medida está reservada para la seda y los hilos artificiales y sintéticos.
      .py-4.py-md-0(titulo="<strong>Sistemas indirectos</strong>")
        .row(style='background-color: #FEF5E5')
          .col-6.p-5
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta3/imagen2.png')
          .col-md-6.p-5
            p (Peso constante y longitud variable). Cuanto más elevado es el número, más fino es el hilado o fibra.
            p <strong>Número métrico (Nm):</strong> número de metros que pesan un gramo o miles de metros por kilogramo. (el más utilizado).
            p <strong>Número inglés (Ne):</strong> número de madejas de 840 yardas que pesan una libra, (el más habitual para el algodón).
            p <strong>Número catalán (Na):</strong> número de madejas de 777,5 m que pesa 440 gramos.
            p Esta numeración describe el calibre o grosor.
            p <strong>El primer número:</strong> representa los estirajes que ha recibido el hilo cuando se está elaborando. 
            p Así, entre más estirajes ha recibido, más delgado será.
            p El número que está después del slash (raya), representa el número de Hebra (cabos) que forman el hilo. 
                
    .row.mb-5.mt-5.justify-content-center.align-items-center
      .col-md-8
        .cajon.color-primario.p-4
          p.mb-0 <strong>¿Para qué elegir el calibre?</strong>
          p.mb-0 La selección de calibre del hilo depende de la clase de tela y de prenda que va a coser. El tipo de tejido a trabajar, según la necesidad. El calibre de la aguja varía según el tejido e hilo.
          
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .tarjeta(style='background-color: #673AB7')
          .row.justify-content-center.align-items-center
            .col-1.col-md-1.d-none.d-lg-block
              img.mr-3.mt-mb-3(src="@/assets/curso/temas/tema3/hilo.png")
            .col-sm-12.col-md-10.col-lg-10
              .row.justify-content-center.align-items-center
                .col-sm-10.col-md-10.col-lg-10.mb-3.mb-sm-0
                  h3.mt-3.text-white Clasificación de los hilos
                  p.mb-3.text-white Revisa el video que pueden resultar útil para conocer más sobre la clasificación de los hilos.
                .col-sm-2-col-md-2.col-lg-2
                  a.boton.color-boton(href="https://youtu.be/qUdbl6B18Bg" target="_blank")
                    span.texto-negro Ir al sitio
                    i.fas.fa-video

    Separador

    .row.mb-5
      #t_3_4.titulo-segundo.color-primario
        h2 3.4.  Clasificación de tejidos
      p Los tejidos son una composición de fibras o hilos que en su unión generan características como ancho, largo, grosor, resistencia, que permiten asignarle al tejido ciertas características, las cuales son primordiales en la segmentación o clasificación, como lo son los tejidos planos, tejidos de punto o aglomerados.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/imagen9.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 <strong>¿Qué son los tejidos? </strong>
          br
          br
          | Manufacturado de fibras o hilos que tienen una relación sustancial entre su longitud, área y su espesor con suficiente resistencia mecánica para otorgarle una cohesión

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Clasificación de los tejidos
    
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
      .row(titulo="Telas tejidas")
        .col-md-6.mb-4.mb-md-0
          p <strong>Plano</strong>
          p <strong>Ligamentos fundamentales</strong>
          ul.lista-ul--color.vmorada.mb-0
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Tafetán
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Sarga (diagonal)
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Raso
          p <strong>Ligamentos derivados</strong>
          ul.lista-ul--color.vmorada.mb-0
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Esterilla / panamá / canasta.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Espina / espiga.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Sarga interrumpida (<em>broken twill</em>).
          p <strong>Otros</strong>
          ul.lista-ul--color.vmorada.mb-0
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | <em>Dobby</em>, <em>jacquard</em>, riso, afelpados, etc.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema3/acordeon1/imagen1.png', alt='Textura')
      .row(titulo="Telas no tejidas")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul--color.vmorada.mb-0
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Interlones – guatas.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema3/acordeon1/imagen2.png', alt='Textura')

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Urdimbre y trama

    .tarjeta--container.row
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema3/tarjeta4/imagen1.png')          
        h3.text-center Urdimbre
        p La serie longitudinal de los hilos recibe el nombre de urdimbre y cada uno de los elementos que la constituyen se denomina hilo. Los hilos verticales son la urdimbre.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema3/tarjeta4/imagen2.png')
        h3.text-center Trama
        p La serie transversal recibe el nombre de trama y cada una de sus unidades se denomina pasada. Las pasadas horizontales son la trama.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Diferentes direcciones del hilo de la tela

    .row.justify-content-center.mb-5
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/tarjeta5/imagen1.png")
          .crd_hover_txt--body
            h4.mb-3 Urdimbre
            p.mb-0 La dirección de los hilos verticales es la urdimbre, en la misma dirección en la que va el orillo de la tela. Es más fuerte, estable y no suele ceder.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/tarjeta5/imagen2.png")
          .crd_hover_txt--body
            h4.mb-3 Sesgo o bies
            p.mb-0 Cuando se coloca el patrón a 45° grados con respecto a la dirección de la urdimbre de la tela, aportará mejor caída y cierta elasticidad.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema3/tarjeta5/imagen3.png")
          .crd_hover_txt--body
            h4.mb-3 Trama
            p.mb-0 Es más fina y en ocasiones puede contener fibras elásticas, ya que estas fibras ceden al estirar la tela de orilla a orilla. Cortar en diferentes direcciones en la tela.

    .row.mb-5.mt-5.p-5
      .col-lg-11.position-relative
        .avatar
          figure
            img(src="@/assets/curso/temas/tema3/imagen10.svg")
        .row
          .col-10.ps-5(style='background-color: #D1BCFF')
            .row.mt-3.mb-3
              .col-5(style='font-size: 13px')
                ul.lista-ul--color.vmorada.fa-ul
                  li.mb-0 
                    i.lista-ul__vineta.mb-0
                    | <strong>Tejido plano - Ligamentos fundamentales</strong> 
                  li.mb-0
                    i.lista-ul__vineta.mb-0
                    | <strong>Tejido plano - Ligamentos Derivados</strong>
                  li.mb-0
                    i.lista-ul__vineta.mb-0
                    | <strong>Tejido plano - Otros ligamentos</strong>
                  li.mb-5 
                    i.lista-ul__vineta.mb-0
                    | <strong>Tejido de punto </strong> 
                  li.mb-0
                    i.lista-ul__vineta.mb-0
                    | <strong>Tejido de punto - Por trama </strong> 
                  li.mb-0
                    i.lista-ul__vineta.mb-0
                    | <strong>Tejido de punto - Por urdimbre</strong> 
                  li.mb-0
                    i.lista-ul__vineta.mb-0
                    | <strong>No tejido</strong> 
              .col-5(style='font-size: 13px')  
                ul.lista-ul--color.vmorada.fa-ul
                  li.mb-0 
                    i.fas.fa-angle-right.mb-3
                    | Tafetán - Sarga - Raso o Satín
                  li.mb-0
                    i.fas.fa-angle-right.mb-3
                    | Esterilla 2x1 - Espina - Broken- Esterilla 2x2 – #[em Dobby]
                  li.mb-0
                    i.fas.fa-angle-right.mb-2
                    | #[em Corduroy] – Terciopelo
                  li.mb-0
                    i.fas.fa-angle-right.mb-3
                    span.mb-2 Proceso de fabricación de telas en que se utilizan agujas para formar una serie de mallas entrelazadas a partir de uno o más hilos, o bien, un conjunto de hilos. 
                  li.mb-0 
                    i.fas.fa-angle-right.mb-3
                    | Sencillo, #[em jersey], doble.
                  li.mb-0
                    i.fas.fa-angle-right.mb-3
                    | #[em Tricot, raschell.]
                  li.mb-0
                    i.fas.fa-angle-right.mb-3
                    | Tipo de telas producidas al formar una red con fibra que se unen por procedimientos mecánicos, térmicos o químicos, pero sin ser tejidas. Fieltros o aglomerados - Películas – Espumas

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Color de las telas
      p Crudo - Pre Teñido - Teñido en pieza - Blanco – Estampado.

    Separador

    .row.mb-4
      #t_3_5.titulo-segundo.color-primario
        h2 3.5 Caracterización de los tejidos
      p Los textiles suelen ser organizados en función de su comportamiento, esto permite que la idea o el desarrollo de producto sea mucho más certero y esté enfocado al requerimiento funcional del diseño.

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Caracterización de los textiles
 
    .row.align-items-center.justify-content-center.mb-4
      .col-lg-10.p-3
        .row
          .col-3.position-relative
            .avatar
              img(src="@/assets/curso/temas/tema3/imagen12.svg")
          .col-8.p-5(style='background-color: #FEF5E5')
            .row
              .col-12
                p Se organizan en función de su comportamiento, está relacionado con el peso del material:
                .row
                  .col-3
                    ul.lista-ul
                      li.mb-0
                        i.lista-ul__vineta
                        | Estructura
                      li.mb-0
                        i.lista-ul__vineta
                        | Fluidez
                  .col-3
                    ul.lista-ul
                      li.mb-0
                        i.lista-ul__vineta
                        | Expansión
                      li.mb-0
                        i.lista-ul__vineta
                        | Compresión

    .tarjeta.color-acento-contenido.p-3
      SlyderA(tipo="b")
        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estructura
            p.mb-0 Las telas estructuradas proporcionan el cuerpo de la prenda, dan forma por sí mismas. Caída: la tela ha de mantenerse en su lugar y no caer cuando se le suelta.
            p.mb-0 División de telas con estructura en diferentes áreas según su ocasión de uso: formal, informal, <em>sport</em>.
            p.mt-4 <strong>Textiles</strong>
            p Paño - <em>Tweed</em> - <em>Jacquard</em> - Pana - Lino - <em>Oxford</em> - <em>Faya</em> - <em>Shantung</em> - Popelina - Tafetán - Bengalina – Satén.
            p <strong>Textiles plastificados - Recubiertos</strong>
            p Microfibras de <em>nylon</em> y <em>poliester</em>, algunas veces con propiedades hidrófugas.
          .col-sm-5.p-2
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta6/imagen1.png')
        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Fluidez
            p Estas telas son suaves y fluidas, incapaces de sostener su propio peso debido a su caída natural. La fluidez de estas telas está intrínsecamente ligada al tipo de hilo empleado en su fabricación, que suele ser altamente torsionado, ya sea de hebras hiladas o de multifilamento. Al caer sobre el cuerpo, estas telas son generalmente ligeras y de peso medio.
            p <strong>Textiles</strong>
            p <em>Chiffon</em> - Gasa - <em>Chalis</em> - <em>Interlock</em> - <em>Georgette</em> - <em>Crepé</em> - <em>Jersey</em> - Malla - Encaje - Género – <em>Velvet</em> / terciopelo - <em>Lamé</em> - <em>Crepé</em> texturizado - Género de punto.
          .col-sm-5.p-2
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta6/imagen2.png')
        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Expansión
            p En el grupo de textiles por expansión se incluye el concepto del plisado, este efecto permite expandir la silueta. El concepto de acolchado se incluye en esta categoría, este es un método natural para crear calidez mediante la combinación de capas de tela, se puede aplicar el acolchado medio y acolchado grueso.
            p <strong>Textiles</strong>
            p Acolchado - Redecillas - Tarlatana - De piel o peluche - Tules - Organza - Plisados - <em>Crepé</em> de <em>satén</em> plisados.
          .col-sm-5.p-2
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta6/imagen3.png')
        .row.p-5
          .col-md-6.mb-4.mb-md-0
            h3 Compresión
            p El objetivo principal de este es crear ajuste perfecto a la silueta humana. El grado de elasticidad, dependerá del tipo y cantidad de hilos elásticos.
            p <em>Stretch confort</em>: tejidos con un 2 % a 5 % de fibra de spandex, proporciona una compresión suave.
            p <em>Stretch fuerte</em>: contiene un 14 % a 20 % de fibra de spandex, proporciona una compresión continua que resta silueta al cuerpo.
            p <strong>Textiles</strong>
            p Punto canalé - Pana <em>stretch</em> - <em>Power lycra</em> - Punto de algodón <em>stretch</em> - Doble punto - <em>Power net</em>.
          .col-sm-6.p-2
            figure
              img(src='@/assets/curso/temas/tema3/tarjeta6/imagen4.png')
             
    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Las entretelas

    .row.align-items-center.justify-content-center
      .col-lg-10
        .row
          .col-1.position-relative
            .avatar
              img(src="@/assets/curso/temas/tema3/signo-de-interrogacion.png")
          .col-11.justify-content-center.align-items-center.borde-redondo.p-4(style='background-color: #D1BCFF')
            .row
              .col-1
              .col-11
                p Son la estructura de nuestra ropa, ya que sostienen y refuerzan las áreas críticas. El tipo de entretela usada determina el tacto, la forma y la durabilidad de nuestra prenda, manteniendo su función y ayudando en el proceso productivo.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Tipos de entretelas
      p Estas pueden ser agrupadas de acuerdo con la tela, aplicación y estiraje, dentro de estas se encuentra:

    .row.justify-content-center.align-items-center.mb-5
      .col-9
        .row.align-items-center.justify-content-center(style='background-color: #FEF5E5')
          .col-3
            ul.lista-ul--color.vmorada.fa-ul.mt-3.mb-3
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Entretelas tejidas
          .col-3
            ul.lista-ul--color.vmorada.fa-ul.mt-3.mb-3
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Entretelas no tejidas
          .col-3     
            ul.lista-ul--color.vmorada.fa-ul.mt-3.mb-3
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Entretelas de punto
                      
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema3/tarjeta7/imagen1.png')          
        h3.text-center Entretelas tejidas
        p Pueden ser de algodón, rayón, lana, poliéster o mezclas de fibras. Se tejen de la misma forma que las telas normales (urdimbre / trama). 
        p Usualmente, cuando se cortan al sesgo, estiran más y se utilizan entonces para dar forma.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img.p-5(src='@/assets/curso/temas/tema3/tarjeta7/imagen2.png')
        h3.text-center Entretelas NO tejidas
        p Por lo general están hechas de poliéster, rayón, nylon o una mezcla de diferentes fibras.
        p Las fibras son distribuidas al azar y juntadas por acción química o térmica. 
        p Ya que no tienen una dirección de hilo o grano, no se desmechan y pueden ser cortadas en cualquier dirección o ángulo.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ ¿Cómo elegir la entretela adecuada?

    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
      .row(titulo="Fabricación y aplicación")
        .col-md-10.mb-4.mb-md-0
          p Las entretelas pueden ser tejidas, no tejidas o de punto. Pueden usarse fusionándose, cosiéndose
      .row(titulo="Elásticas o estables")
        .col-md-10.mb-4.mb-md-0
          p Las entretelas se catalogan bajo estas dos categorías: 
          p <strong>Las elásticas:</strong> donde se requiere dar forma.
          p <strong>Las estables:</strong> en sitios de la prenda donde se necesite fijar.
      .row(titulo="Cuidado")
        .col-md-10.mb-4.mb-md-0
          p La tela exterior debe tener características similares de la entretela.
      .row(titulo="Color")
        .col-md-10.mb-4.mb-md-0
          p El color se transparenta a través de algunas telas. Se debe seleccionar una entretela compatible con el color de la tela exterior. 
      .row(titulo="Peso")
        .col-md-12.mb-4.mb-md-0
          p Los pesos de las entretelas varían desde las muy livianas hasta las muy pesadas. Se deben elegir de acuerdo con el material a trabajar. 
      .row(titulo="Métodos de aplicación")
        .col-md-12.mb-4.mb-md-0
          p Los pesos de las entretelas varían desde muy livianos hasta muy pesados, y deben seleccionarse de acuerdo con el material que se va a trabajar. 
      .row(titulo="Entretelas termoadhesivas")
        .col-md-12.mb-4.mb-md-0
          p Van cubiertas por uno de sus lados por un agente adhesivo sensible al calor; al someterlas a humedad y calor, el agente adhesivo se funde y se adhiere a la tela. 
      .row(titulo="Fusionado mecánico")
        .col-md-10.mb-4.mb-md-0
          p Se requiere de una máquina en perfectas condiciones para obtener un buen resultado.
          p Únicamente el balance exacto de temperatura, presión y tiempo pueden garantizar una adherencia perfecta.
      .row(titulo="Fusionado manual")
        .col-md-12.mb-4.mb-md-0
          p Debe tener en cuenta el tipo de entretela, algunas se fusionan con vapor y presión y otras con una plancha seca sin vapor. Debe tener una adecuada temperatura la plancha, vapor o sin vapor, húmedo o seco. 
      .row(titulo="Fusionado cosibles")
        .col-md-12.mb-4.mb-md-0
          p Las entretelas cosibles se unen a la tela o a las costuras de una prenda, ya sea a mano o a máquina. Son especialmente útiles para textiles con textura, como el terciopelo, así como para aquellos sensibles al calor, incluyendo textiles metalizados o plastificados que no toleran la presión o el calor directo de la plancha. 

    
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .tarjeta(style='background-color: #673AB7')
          .row.justify-content-center.align-items-center
            .col-1.col-md-1.d-none.d-lg-block
              img.mr-3.mt-mb-3(src='@/assets/curso/temas/tema3/imagen13.png')
            .col-sm-12.col-md-10.col-lg-10
              .row.justify-content-center.align-items-center
                .col-sm-10.col-md-10.col-lg-10.mb-3.mb-sm-0
                  h3.mt-3.text-white Caracterización de los textiles
                  p.mb-3.text-white Revisa el documento que pueden resultar útil para conocer más sobre la caracterización de los textiles.
                .col-sm-2-col-md-2.col-lg-2
                  a.boton.color-boton(href=" https://youtu.be/mc1kARHDHrs" target="_blank")
                    span.texto-negro Ir al sitio
                    i.fas.fa-file-download

    Separador
    
    .row.mb-4
      #t_3_6.titulo-segundo.color-primario
        h2 3.6 Procesos textiles
      p.mb-5 Los tratamientos posteriores a las operaciones de coloración tienen por objeto mejorar el aspecto y las propiedades de los materiales textiles antes de su comercialización, así como proporcionarles algunas cualidades que mejoren su comportamiento al uso y mantenimiento. También eliminar o minimizar algunas cualidades no deseables de los mismos.

    .row.mb-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Tipos de operaciones

    .row.align-items-center.justify-content-center.mb-5
      .col-4
        .row.borde-redondo.p-3(style='background-color: #673AB7')
          .col-3.position-relative.p-4
            .avatar
              img(src="@/assets/curso/temas/tema3/avatar4/imagen1.png")
          p.text-white <strong>Aprestos</strong>
          p.text-white(style="font-size: 18px") Cuando los efectos conseguidos se deben a la aplicación de productos químicos, tales como: rigidez, estabilidad, tactosidad, impermeabilizar o aumentar su peso.
      .col-1
      .col-4
        .row.borde-redondo.p-3(style='background-color: #D1BCFF')
          .col-3.position-relative.p-4
            .avatar
              img(src="@/assets/curso/temas/tema3/avatar4/imagen2.png")
          p <strong>Acabados</strong>
          p(style="font-size: 18px") Cuando los efectos conseguidos se deben a la aplicación de tratamientos físicos y/o mecánicos, tales como: calor, presión, humedad, etc.
    
    .row.mb-5
      p Ambos tipos de operaciones no son incompatibles entre sí; más bien al contrario, se combinan con frecuencia para la obtención de los efectos perseguidos. Proceso realizado sobre la fibra, el hilo, la tela o la prenda, con el fin de modificar alguna de sus características:

    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .row.justify-content-center.align-items-center(style='background-color: #FEF5E5')
          .col-1
          .col-4.align-items-center
            ol.lista-ol--cuadro.fa-ol.mb-3.mt-3
              li.mb-0 
                .lista-ol--cuadro__vineta(style='color: black')
                  span.mb-0 1
                p.mb-0 Apariencia
          .col-3.align-items-center
            ol.lista-ol--cuadro.fa-ol.mb-3.mt-3
              li.mb-0 
                .lista-ol--cuadro__vineta(style='color: black')
                  span.mb-0 2
                p.mb-0 Tacto
          .col-4.align-items-center
            ol.lista-ol--cuadro.fa-ol.mb-3.mt-3
              li.mb-0 
                .lista-ol--cuadro__vineta(style='color: black')
                  span.mb-0 3
                p.mb-0 Comportamiento    

    .row.align-items-center.justify-content-center.p-2.pmb-5
      .col-md-4
        .bloque-texto-c.borde-redondo.color-acento-contenido.p-4
          p.text-center(style="color: #673AB7") <strong>Acción que lo origine / modifica característica:</strong>
          p <strong>> Físico/estético</strong> 
          p No modifica la estructura interna de la fibra, solo apariencia.
          p <strong>> Químico/funcional</strong>
          p Modifica propiedades estéticas y/o funcionales de la estructura interna de la fibra.
          p <strong>> Químico-físico / estético-funcional</strong>
      .col-md-4
        .bloque-texto-c.borde-redondo.color-acento-contenido.p-4
          p.text-center(style="color: #673AB7") <strong>Acción que lo origine / modifica característica:</strong>
          p <strong>> Temporal</strong> 
          p Algunas lavadas.
          p <strong>> Permanente</strong>
          p Acabados físicos, vida útil de la prenda.
          p <strong>> Renovable</strong>
          p Puede renovarse en el hogar o tintorería.
      .col-md-4
        .bloque-texto-c.borde-redondo.color-acento-contenido.p-4
          p.text-center(style="color: #673AB7") <strong>Limpieza</strong>
          p <strong>> Desgomado de la seda</strong> 
          p <strong>> Descrude del algodón</strong> 
          p <strong>> Lavado de lana</strong> 
          br
          br
          br
          br
          br

    .row.align-items-center.justify-content-center.p-2.mb-5
      .col-md-4
        .bloque-texto-c.borde-redondo.color-acento-contenido.p-4
          p.text-center(style="color: #673AB7") <strong>Diseño y color</strong>
          p El uso de tintes que penetran y dan color a las fibras. Se usa para dar color y crear grafías.
      .col-md-4
        .bloque-texto-c.borde-redondo.color-acento-contenido.p-4
          p.text-center(style="color: #673AB7") <strong>Textura</strong>
          p El uso de tintes que penetran y dan color a las fibras. Se usa para dar color y crear grafías.
      .col-md-4
        .bloque-texto-c.borde-redondo.color-acento-contenido.p-4
          p.text-center(style="color: #673AB7") <strong>Diseño y color</strong>
          p Se utiliza para mejorar la textura de su superficie y el tacto.

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Diseño y color - teñido

    .row.mb-5.align-items-center
      .col-6.p-3(style='background-color: #DADDDF')
        p #[b Métodos:] fibras, hilos, teñir en solución, materia prima, piezas.
    
    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Diseño y color - estampado

    .row.mb-5.align-items-center
      .col-6.p-3(style='background-color: #DADDDF')
        p Rotativa, serigrafía, sublimación, transfer digital.

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Textura

    .row.mb-5.align-items-center
      .col-12.p-3(style='background-color: #DADDDF')
        p Calandrar satinado, glaseado, afelpado o napping, mercerizado y sanforizado, reducción de brillo, grabado, gofrado, aumento de cuerpo - sizing, encerado ciré, moiré.

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Desempeño

    .row.mb-5.align-items-center
      .col-12.p-3(style='background-color: #DADDDF')
        p Resistencia a pliegues y arrugas, planchado durable, repelente al agua / impermeabilización, control de encogimiento, resistencia a la suciedad, antiestática, antibacterial, resistente a polillas, ignición retardada, resistencia al moho.

    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .tarjeta(style='background-color: #673AB7')
          .row.justify-content-center.align-items-center
            .col-1.col-md-1.d-none.d-lg-block
              img.mr-3.mt-mb-3(src='@/assets/curso/temas/tema3/imagen14.png')
            .col-sm-12.col-md-10.col-lg-10
              .row.justify-content-center.align-items-center
                .col-sm-10.col-md-10.col-lg-10.mb-3.mb-sm-0
                  h3.mt-3.text-white Acabados
                  p.mb-3.text-white Revisa el video que pueden resultar útil para conocer más sobre los acabados.
                .col-sm-2-col-md-2.col-lg-2
                  a.boton.color-boton(href="https://youtu.be/RecKnCBkD5g" target="_blank")
                    span.texto-negro Ir al sitio
                    i.fas.fa-file-download


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
