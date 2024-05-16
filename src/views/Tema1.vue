<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Diseño y moda

    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.1  Fundamentación de moda
    
    .row.mb-0
      p En la actualidad una de las mayores falencias en la industria de la moda, es la articulación entre el diseñador (área creativa) y el patronista (área operativa); por lo tanto, es importante ofrecer al patronista una contextualización en el manejo de la terminología y así afianzar la articulación entre las dos áreas.

    .row
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-botones(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 ¿Qué es diseño?
              p Diseño viene del italiano disegnare que significa dibujar, que a su vez se deriva del latín designare que evoca marcar, trazar, ordenar y disponer. El diseño es una actividad creativa orientada a soluciones idóneas a ciertas problemáticas. 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tarjeta1/imagen1.svg')})`}")
              .tarjeta-slide_contenido.p-4.mt-5
                br
                br
                br
                br
                br
                br
                br
                br
                br 
                h1.text-center ¿Qué es diseño?

      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.abajo.color-acento-botones(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas//tema1/tarjeta1/imagen2.svg')})`}")
              .tarjeta-slide_contenido.p-4.mt-5
                br
                br
                br
                br
                br
                br
                br
                br
                br
                h1.text-center ¿Qué es moda?
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 ¿Qué es moda?
              p La definición viene del francés mode, y éste del latín modus, "modo" o "medida". La moda regula las elecciones que hacen las personas, definiendo ciertos patrones de comportamiento dentro de un grupo social; indica a la gente qué debe consumir, utilizar o hacer.

      .col-sm-6.col-xl-4.mb-4.mb-sm-0
        .tarjeta.tarjeta-slide.derecha.color-acento-botones(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas//tema1/tarjeta1/imagen3.svg')})`}")
              .tarjeta-slide_contenido.p-4.p-xl-5
                br
                br
                br
                br
                br
                br
                br
                br
                br
                h1.text-center ¿Qué es diseño de moda?
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 ¿Qué es diseño de moda?
              p Producción de indumentaria para el sistema de moda, donde su principal foco es la innovación y la interpretación, respondiendo a una necesidad de manera funcional.
    
    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Evolución de la moda
      p La moda ha ido evolucionando con el pasar de los años teniendo en cuenta diferentes factores que han afectado la sociedad. Quienes han aportado a estos cambios diferenciadores en la moda han dejado una gran huella.

    .row(style='background-color: #D1BCFF')
      .col-1
      .col-3
        figure
          img(src='@/assets/curso/temas/tema1/imagen1.svg', alt='Modista') 
      .col-7.p-xl-5.mt-4
        p El vestirse surge desde el momento en que las prendas pasan de ser una obligación de protegerse del clima a convertirse en una necesidad vital. 
        br
        p El vestido muestra la cultura, riqueza y grado de desarrollo de las civilizaciones y da una visión de las condiciones geográficas, económicas y culturales de los pueblos.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Historia del vestuario
      p Es un reflejo de los cambios sociales, políticos y culturales que tienen lugar alrededor del mundo a medida de los años. Conforme el humano ha evolucionado, también lo ha hecho su vestimenta e indumentaria.
      .col-1
      .col-10
        figure
          img(src='@/assets/curso/temas/tema1/linea-tiempo.svg', alt='Línea de tiempo')
    
    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Evolución de las prendas
      p Las prendas han ido evolucionando con el pasar de los años teniendo en cuenta diferentes factores. Estos factores determinan la decisión que toma cada persona para elegir que ponerse a diario.

    
    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta2/imagen1.svg' alt='AvatarTop')
        h2.text-center Físicos
        p.text-center Clima, edad, estructura, género, salud.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta2/imagen2.svg' alt='AvatarTop')
        h2.text-center Sociales - culturales
        p.text-center Clases sociales, labor, religión, trajes típicos..

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta2/imagen3.svg' alt='AvatarTop')
        h2.text-center Psicológicos
        p.text-center Estados de ánimo, desórdenes, autoestima.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta2/imagen4.svg' alt='AvatarTop')
        h2.text-center Sexualidad
        p.text-center Orientación sexual, indumentaria.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta2/imagen5.svg' alt='AvatarTop')
        h2.text-center Moda
        p.text-center Historia, mercadotecnia, identidad.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ ¿Por qué nos vestimos?

    LineaTiempoD.color-primario
      .row(numero="1" titulo="Físicos")
        .col-md-12.mb-4.mb-md-0(style='background-color: white')
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.lista-ul__vineta
                | <strong>Clima:</strong> el clima influye según la geografía, dependiendo de la temporada del año las prendas se acomodan teniendo en cuenta que en algunos países tiene 4 estaciones o climas estables. 
              li 
                i.lista-ul__vineta
                | <strong>Edad:</strong> las prendas es uno de los aspectos que debe evolucionar conforme a la etapa/edad que se vive. Para cada edad hay un estilo que encaja con la condición de cada persona. 
              li 
                i.lista-ul__vineta
                | <strong>Estructura corporal:</strong> la estructura varía depende del tipo de cuerpo, la talla, la contextura. Cada cuerpo de acuerdo con su estructura corporal tiene prendas que le favorecen más que otras.
              li 
                i.lista-ul__vineta
                | <strong>Género:</strong> el género ha venido evolucionando en los últimos años, actualmente existe una gran diversidad de personas que no se identifican con un género en particular. Las marcas optan por ropa unisex - sin género.
              li 
                i.lista-ul__vineta
                | <strong>Salud:</strong> teniendo en cuenta el estado de salud que se presente, existen muchas prendas que se adaptan. Algunas prendas deben adaptarse o construir con cierta especialidad.
          br
          figure
            img(src='@/assets/curso/temas/tema1/acordeon1/imagen1.svg', alt='Mostrando prendas de vestir')

      .row(numero="2" titulo="Sociales - culturales")
        .col-md-12.mb-4.mb-md-0(style='background-color: white')
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.lista-ul__vineta
                | <strong>Estatus o clases sociales:</strong> está ligado con el poder adquisitivo y el presupuesto que invierta cada persona. Depende de esto se determina la cantidad de prendas y la calidad. Aspiracional: querer aparentar ser de una clase social - "wannabe". 
              li 
                i.lista-ul__vineta
                | <strong>Religión:</strong> existe en el mundo muchas clases de normas ortodoxas que imponen ciertas reglas de indumentaria que se deben respetar de acuerdo con dichas creencias. 
              li 
                i.lista-ul__vineta
                | <strong> Actividad laboral:</strong> uniformes laborales de acuerdo con la profesión, tienen logos institucionales, vestidos de acuerdo con la imagen corporativa de la empresa. Algunas normas de seguridad y salud en el trabajo.

              li 
                i.lista-ul__vineta
                | <strong>Trajes típicos:</strong> los trajes típicos corresponden a la indumentaria que expresa la identidad cultural de una región, pueblo, cultura o nación. Estas prendas se pueden utilizar para el uso cotidiano o para eventos especiales.
              li 
                i.lista-ul__vineta
                | <strong>Tribus urbanas:</strong> personas que comparten un universo de intereses comunes.
          br
          figure
            img(src='@/assets/curso/temas/tema1/acordeon1/imagen2.svg', alt='Mujeres de raza negra')

      .row(numero="3" titulo="Psicológicas")
        .col-md-12.mb-4.mb-md-0(style='background-color: white')
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.lista-ul__vineta
                | <strong>Estado de ánimo:</strong> el estado de ánimo determina la manera de vestir al iniciar el día; poderoso, triste, feliz, deprimido, entre otros. 
                br
                br
                | "Cuando estamos estresados, utilizamos solo un 90% de prendas que guardamos en nuestro guardarropa".(Harpersbazaar, 2019). 
          br
          figure
            img(src='@/assets/curso/temas/tema1/acordeon1/imagen3.svg', alt='Mujer en un vestier')

      .row(numero="4" titulo="Sexualidad")
        .col-md-12.mb-4.mb-md-0
          .col-sm.mb-5.mb-sm-0
          p Depende de todas las anteriores: cultural, físico, social, psicológico, no solo depende de la orientación sexual si no también el lenguaje de sexualización de la indumentaria, el sentirse sexy o atractivo para otra persona. 
          p También hay prendas de vestir con una finalidad erótica.
          br
          figure
            img(src='@/assets/curso/temas/tema1/acordeon1/imagen4.svg', alt='Tres mujeres amigas')

      .row(numero="5" titulo="Desórdenes")
        .col-md-12.mb-4.mb-md-0(style='background-color: white')
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.lista-ul__vineta
                | <strong> Mentales:</strong> cuestiones de autoestima, personas que pueden ser introvertidas o extrovertidas, algunas se esmeran para mostrarse. 
              li
                i.lista-ul__vineta
                | <strong> Alimenticios:</strong> depende de cómo se siente respecto a su propia imagen y a su propio cuerpo. 
          br
          figure
            img(src='@/assets/curso/temas/tema1/acordeon1/imagen5.svg', alt='Mujer con cara de desagrado en un closet')

      .row(numero="6" titulo="Moda")
        p Puede constituir un pensamiento histórico en un momento determinado de la época. Cómo vestirse según la mercadotecnia, tendencias de moda, temporadas y diseñadores. Se incentiva a las personas a que consuman y se "actualicen". En este sentido, existen dos grupos de personas:
        .col-md-12.mb-4.mb-md-0(style='background-color: white')
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.lista-ul__vineta
                | <strong> Fashion victims:</strong> personas adictas al consumismo, al último grito de la moda, principales compradores del fast fashion. 
              li
                i.lista-ul__vineta
                | <strong> Fashionistas:</strong> personas que llevan a un extremo la moda, invierten en prendas costosas, únicas o de alta costura, para afirmar su identidad u originalidad; combinan lo nuevo con lo vintage, son compradores activos, que están al corriente de las tendencias actuales.. 
          br
          figure
            img(src='@/assets/curso/temas/tema1/acordeon1/imagen6.svg', alt='Mujer con bolsas de compra a cada lado de la mano')

    br
    .row.mb-5
      .tarjeta.actividad.p-3.color-primario
        .row.justify-content-around.align-items-center      
          .col-1.justify-content-around.align-items-center
            figure
              img(src='@/assets/curso/temas/tema1/imagen2.png', alt='Maniquí')
          .col-8.justify-content-around.align-items-center
            h3 Fundamentación de moda
            p Revisa el documento que pueden resultar útil para aprender más sobre la fundamentación de moda.
          .col-2.justify-content-around.align-items-center
            a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
              span Descargar
              i.fas.fa-puzzle-piece

    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.2  Universos de vestuario
    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Gamas de mercado, Universos de vestuarios - ocasiones de uso.
    .row.mb-4
      p Son conceptos de moda que responden a la necesidad de categorizar, segmentar y agrupar prendas de vestir, accesorios e indumentaria con características similares; los cuales deben ser organizados según el consumidor o mercado objetivo de cada marca. 
      br
      p Cuando se habla de determinantes o factores del ¿por qué? nos vestimos, el mercado no se queda atrás, la segmentación, gamas de mercados, categorización de productos frente a los escenarios del consumo va de la mano con la categorización de las prendas.

    .row.bm-4
      .col-1(style='background-color: #FEF5E5')
      .col-7(style='background-color: #FEF5E5')
        br
        col-sm.mb-5.p-5
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 1
              | <strong>Gama de mercado:</strong> Conjunto de productos de un segmento de mercado que una empresa ofrece a sus consumidores.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | <strong>Gama:</strong> Cualquier serie de cosas que varían gradualmente.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | <strong>Mercado:</strong> Espacio físico o virtual en el que tienen lugar transacciones económicas.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | <strong>Consumidor:</strong> Es un agente económico con una serie de necesidades.
            li 
              .lista-ol--cuadro__vineta
                span 5
              | <strong>Segmento:</strong> Es una parte o algo que junto con otras se encuentra formando un todo.
      .col-3.p-3(style='background-color: #FEF5E5')
        img(src='@/assets/curso/temas/tema1/imagen3.svg', alt='Vestier')
      .col-1(style='background-color: #FEF5E5')

    .row.mb-4
    .row.mb-4
      p En gamas de mercado para el sistema moda, se encuentran movimientos que se han ido adaptando a lo largo de la historia, a través de las necesidades, evoluciones y revoluciones, cada una de las segmentaciones son movimientos transitorios, algunos de ellos perdurando con el paso de los años:

    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta3/imagen1.svg' alt='AvatarTop')
        p.text-center Principales
        p.text-center Haute couture, pret a porter, fast fashion, slow fashion.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta3/imagen2.svg' alt='AvatarTop')
        p.text-center Transitorias
        p.text-center Vegan fashion, ethical fashion, eco fashion, circle fashion.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta3/imagen3.svg' alt='AvatarTop')
        p.text-center Haute couture / <strong>Alta costura</strong>
        p.text-center Prendas exclusivas a la medida del cliente. Prendas hechas a medida, de forma artesanal.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta3/imagen4.svg' alt='AvatarTop')
        p.text-center Pret a Porter / <strong>Listo para llevar</strong>
        p.text-center Prendas producidas en serie con patrones que se repiten. Industrialización de la moda. No son personalizadas ni exclusivas. Ready to wear.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta3/imagen5.svg' alt='AvatarTop')
        p.text-center Fast Fashion / <strong>Moda rápida</strong>
        p.text-center Trasladar propuestas de grandes casas de diseño, a tiendas para capturar alguna tendencia, lo más rápido posible. Producción de prendas en tiempos muy cortos a un bajo costo - cápsulas.

      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/tarjeta3/imagen6.svg' alt='AvatarTop')
        p.text-center Slow Fashion / <strong>Moda lenta</strong>
        p.text-center Filosofía de consumo responsable. Concienciar sobre el impacto de las prendas de vestir en el medio ambiente, el agotamiento de recursos y la huella que está dejando la industria textil en la sociedad.


    .row.mb-5
      .col-1
      .col-10
        .row.mt-5.p-5(style='background-color: #FEF5E5')
          .titulo-segundo.color-acento-contenido
            h3(style="color: #673AB7") \\\ Universos de vestuario ocasiones de uso
          .col-8.mb-5.p-2
            p(style='font-size: 18px;') Son conceptos que responden a la necesidad de establecer unas categorías bajo las cuales es posible agrupar productos indumentarios de acuerdo con unos parámetros de afinidad y correlación.
            br
            p(style='font-size: 18px;') constituidos por conjuntos de prendas de vestir y accesorios con características similares que deben presentarse agrupados coherentemente bajo conceptos de moda y estar articulados según las necesidades específicas del consumidor o mercado objetivo de cada marca.
          .col-4.p-0
            img(src='@/assets/curso/temas/tema1/imagen4.png' alt='Maniquí')
      .col-1

    .row.mb-5(style='background-color: #F9F6FE')
      .col-1
      .col-9.mb-5
        br
        h3.mb-0 Ocasiones de uso.
        p Protocolario, multi-ocasión, informal, complementos.
        h3.mb-0 Universos de vestuario.
        p Gala, formal, casual, kaki wear, jeanswear, sportswear, activewear, leisurewear - swimwear, beachwear, sleepwear, underwear.
        ul.lista-ul--color
          li.mb-0
            i.lista-ul__vineta
            | Protocolario - gala, forma.
          li.mb-0
            i.lista-ul__vineta
            | Multi-ocasión - casual. 
          li.mb-0
            i.lista-ul__vineta
            | Informal - kaki wear, jeanswear, sportswear, activewear, leisurewear. 
          li.mb-0
            i.lista-ul__vineta
            | Complementos - swimwear, beachwear, sleepwear, underwear.
      .col-2
  
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
      .row(titulo="Protocolario - Formal")
        .col-md-6.mb-4.mb-md-0
          p Surge al momento de la aparición de la alta costura y la necesidad de diferenciar rangos sociales y laborales. Se usa en múltiples actividades como: ceremonias, mundo laboral y corporativo, eventos sociales.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Autocrático.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Jerárquico. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Distintivo. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Diferenciador.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen1.png', alt='Texto que describa la imagen')
      .row(titulo="Multi-ocasión - Casual")
        .col-md-6.mb-4.mb-md-0
          p Nace en los 60's. La participación femenina en el mundo permitió la incursión de nuevas estéticas dinamizando la moda ejecutiva de la época.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Democrático.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Versátil. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Flexible. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Interactivo.      
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Citadino.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen2.png', alt='Texto que describa la imagen')
      .row(titulo="Informal - Kaki wear")
        .col-md-6.mb-4.mb-md-0
          p Nace en los 80's, cuando los llamados YUPI proponen asistir a su entorno laboral de una manera menos formal y rígida en los viernes o actividades menos exigentes. Se usa en múltiples actividades del día a día como: vida universitaria, actividades laborales, informales, tiempo libre.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Dinámico.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Versátil. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Funcional. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Socio flexible.      
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Socio confortable.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen3.png', alt='Texto que describa la imagen')
      .row(titulo="Informal - Jeanswear")
        .col-md-6.mb-4.mb-md-0
          p Nace en lo más profundo de la cultura americana, primero con los mineros y vaqueros. En la década de los 50's se propone para uso cotidiano, de carácter rebelde. En los 80 ́s se convierte en una prenda para ambos sexos.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Dinámico.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Versátil. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Funcional. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Socio flexible.      
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Socio confortable.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen4.png', alt='Texto que describa la imagen')
      .row(titulo="Informal - Sportswear")
        .col-md-6.mb-4.mb-md-0
          p Aparece en los 70’s principalmente influenciado por los juegos olímpicos y por la creciente práctica de los deportes.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Tecnológico.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Multi-Funcional. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Funcional. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Confortable.      
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Apariencia deportiva.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen5.png', alt='Texto que describa la imagen')
      .row(titulo="Informal - Activewear")
        .col-md-6.mb-4.mb-md-0
          p Ropa para hacer ejercicio; cada vez más importante debido a la necesidad de hombres y mujeres por conservar su salud física y mental.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Tecnológico.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Confortable. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Segunda piel. 
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen6.png', alt='Texto que describa la imagen')
      .row(titulo="Informal - Leisurewear")
        .col-md-6.mb-4.mb-md-0
          p Nuevo concepto que surge en el año 2000, parte del estilo freeLance, incluye desde la ropa de dormir hasta aquella diseñada para estar en casa.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Relajado.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Confortable. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Cómodo. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Descanso.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen7.png', alt='Texto que describa la imagen')
      .row(titulo="Complementos - Swim-Beachwea")
        .col-md-6.mb-4.mb-md-0
          p Más que un universo se constituye en una ocasión de uso, sin embargo,deja de lado las prendas para nadar y se complementa con otros artículos, logrando un estilo de descanso y diversión.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Aire libre.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Playa. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Deportes. 
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Recreación.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen8.png', alt='Texto que describa la imagen')
      .row(titulo="Complementos - Sleepwear")
        .col-md-6.mb-4.mb-md-0
          p Ropa para dormir, para uso en horas de descanso dentro del hogar.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Descanso.
            li.mb-0
              i.lista-ul__vineta.mb-0
              | Comodidad. 
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen9.png', alt='Texto que describa la imagen')
      .row(titulo="Complementos - Underwear")
        .col-md-6.mb-4.mb-md-0
          p Ropa  interior, lingerie.
          ul.lista-ul--color
            li.mb-0 
              i.lista-ul__vineta.mb-0
              | Comodidad.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema1/acordeon2/imagen10.png', alt='Texto que describa la imagen')
   
    .row.mb-5.mt-5
      .col-2
      .col-md-8
        .cajon.color-primario.p-4
          p.mb-0 Todas las marcas tienen una categorización de producto; la cual en gran parte se basa por las ocasiones de uso y los universos de vestuario, esto permite tener una mejor segmentación dependiendo de las necesidades del consumidor.
      .col-2
        
    .row.mb-4
      .col-1
      .col-10
        .tarjeta.actividad.p-3.color-primario
          .row.justify-content-around.align-items-center      
            .col-1.justify-content-around.align-items-center
              figure
                img(src='@/assets/curso/temas/tema1/imagen5.png', alt='Maniquí')
            .col-8.justify-content-around.align-items-center
              h3 Universos de vestuario - Gamas de mercado
              p Revisa el documento que puede resultar útil para aprender más sobre los Universos de Vestuario - Gamas de Mercado.
            .col-2.justify-content-around.align-items-center
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Descargar
                i.fas.fa-puzzle-piece
      .col-1

    .row.mb-4
      br
      .titulo-segundo.color-primario.mb-4
        h2 1.3.  Perfil y estilo de consumidor
    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Perfil y estilo de consumidor.
    .row.mb-4
      p Para el análisis de una marca o mercado, se requiere de la categorización de grupos de personas con características similares, estudio que permitirá identificar su comportamiento, consumo e intereses, permitiendo así que el producto o servicio a ofrecer sea mucho más específico y certero con el cliente o nicho de mercado. 
    .row.mb-4(style='background-color: #D1BCFF')
      .col-4.p-5
        img(src='@/assets/curso/temas/tema1/imagen6.png', alt='Maniquí')
      .col-7.p-5
        h3 ¿Quién es el consumidor? 
        p Se entiende por consumidor al individuo que requiere satisfacer cierta necesidad a través de la compra u obtención de determinados productos. El consumidor no es un simple agente PASIVO que espera a que le ofrezcan productos, es un agente ACTIVO con el poder suficiente para lograr cambios en las ofertas y hasta en las mismas empresas, para que se ajusten a sus requerimientos y necesidades.
  
    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Perfil del consumidor
      p.mb-5 Es la descripción de las características de los consumidores de un producto o usuarios de un servicio determinado y un modelo de pensamiento. Es UNA de las variables para la definición de cualquier estrategia de marketing. El perfil NO se determina SÓLO por la edad NI por el segmento socio económico.

    .tarjeta.color-acento-contenido.p-4
      SlyderA(tipo="b")
        .row.p-5
          .col-md-6.mb-4.mb-md-0
            h3 Tradicional
            p Es un consumidor que participa en un ambiente social exigente en el que busca reconocimiento, aceptación y afirmación de los demás; invierte mucho dinero, tiempo y energía en sobresalir y destacarse.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Las tradiciones permanecen.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es rígido, formal y exigente con la etiqueta y el protocolo.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Presenta resistencia al cambio.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Mantiene su estilo a través del tiempo.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es reservado y se toma tiempo para involucrar nuevos conceptos y productos innovadores.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Busca siempre un sello de tradición y distinción.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es fiel a las marcas, busca en ellas el estatus.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Mantiene y aprecia los referentes del pasado.
          .col-sm-6.p-5
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta4/imagen1.svg')

        .row.p-5
          .col-md-6.mb-4.mb-md-0
            h3 Neo tradicional
            p Es un consumidor evolucionado y sintonizado con el desarrollo del entorno. Tiene un mayor nivel de sensibilidad y flexibilidad. Se detiene a observar y se deja influenciar por nuevos referentes, conceptos y propuestas de moda. Mantiene un punto de equilibrio entre la tradición y la innovación, integrando los fenómenos de la moda, la evolución cultural y social a su estilo personal.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Las tradiciones permanecen.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Conserva las normas.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Mantiene el gusto y aprecia la etiqueta y el protocolo, pero no las maneja con rigor.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Involucra fácilmente nuevos conceptos y productos innovadores.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Busca siempre un sello de tradición y distinción.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Busca siempre un sello de tradición y distinción.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Fiel a las marcas, busca en ellas el estatus.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Aprecia los referentes actuales.
          .col-sm-6.p-5
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta4/imagen2.svg')

        .row.p-5
          .col-md-6.mb-4.mb-md-0
            h3 Contemporáneo
            p Surge de los cambios sociales, económicos y tecnológicos de las últimas décadas, dando origen a un nuevo modelo de comportamiento, donde se encuentran un perfil original y auténtico que está en permanente evolución. Es multicultural, dinámico y explorador constante de su propio desarrollo personal, emocional y profesional.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Evoluciona y modifica sus valoraciones.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Tiene definido su propio estilo personal.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | El desarrollo personal y profesional está por encima de lo familiar.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | La mujer juega un rol profesional, laboral, político y familiar.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Sensible al cambio, adopta fácilmente nuevas alternativas para estar en constante evolución.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es dinámico.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es citadino y urbano. 
          .col-sm-6.p-5
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta4/imagen3.svg')

        .row.p-5
          .col-md-6.mb-4.mb-md-0
            h3 Vanguardista
            p Es un destacado grupo social inconforme y extremadamente original. Genera cambios y origina nuevos conceptos, es innovador, rompe esquemas y paradigmas de su entorno directo generando cambios que se reflejan como tendencias globales.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Cambia y modifica fácilmente su escala de valoraciones.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | No tiene apegos ni crea compromisos con ningún formato.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Vive pendiente de lo que surge en las grandes capitales del mundo.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | La innovación es parte de su vida diaria, es cambiante e inestable.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Lo motiva explorar referentes en otras culturas para convertirse en habitante planetario.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Su vida viaja a la velocidad del Internet.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Todo es recibido, aceptado, permitido y adoptado tal vez solo por hoy.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es atrevido, le gusta el juego, el riesgo, lo novedoso.
          .col-sm-6.p-5
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta4/imagen4.svg')
             
        .row.p-5
          .col-md-6.mb-4.mb-md-0
            h3 Exhibicionista
            p Resulta de un deseo personal por destacarse, llamar la atención y proyectarse como “distinto” a los demás. El estilo es lo de menos, la imagen es todo.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Quiere llamar permanentemente la atención y ser distinto de los demás.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Rompe todos los esquemas para no pasar desapercibido.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Concentra su atención en todas aquellas rarezas y excentricidades que el mercado le ofrece o de las que él mismo se apropia.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Prefiere proyectar una imagen nueva a regirse por un canon establecido.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Su apariencia personal es original e innovadora pero extremadamente llamativa.
          .col-sm-6.p-5
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta4/imagen4.svg')

    .row.mb-5.mt-5
      .col-2
      .col-md-8
        .cajon.color-primario.p-4
          p.mb-0 El estilo personal es un proceso creativo constante y atractivo, que evoluciona el ser. 
          br
          P.mb-0 No tiene reglas, excepto las que uno se ponga; las cuales también pueden ser ajustadas.
      
    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Estilos  del consumidor
      p.mb-5 Coherencia entre el ser y el parecer. La relación que tiene el modelo de pensamiento y la actitud personal define el estilo de cada individuo. El estilo refleja todos los aspectos de una persona, el pensamiento, las acciones y la relación con los demás y los objetos, además sus gustos, preferencias, motivaciones, valoraciones necesidades y actividades reflejadas en sus actitudes.

    .row.mb-4(style='background-color: #FEF5E5')
      .col-4.p-5
        img(src='@/assets/curso/temas/tema1/imagen7.png')
      .col-8.p-5.mt-5
        h3 ¿Qué es el estilo?
        p Es una selección y acumulación de vivencias, referentes, culturas e influencias que se prioriza, valora y manifiesta con nuestra actitud y expresión a través de los objetos que elegimos para llevar en nuestra indumentaria y nuestro diario vivir, lo que se contribuye en la coherencia en el habitus, hábito, hábitat que determinará un estilo personal, particular y plural.

    .tarjeta.color-acento-contenido.p-4
      SlyderA(tipo="b")
        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estilo Clásico
            p Obra que se tiene por modelo digno de imitación; genialidad en la idea o diseño donde el valor y el aprecio permanece en el tiempo y son sensibles a evolucionar.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Tener el estilo clásico no quiere decir que se ignoren las tendencias de moda.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es tener prendas claves que se editan, que se pueden combinar y que permanecen en el tiempo.
            p.p-3(style='background-color: #FEF5E5') “¡Innovación! Uno no puede ser innovador por siempre. Yo quiero crear clásicos.”  <strong>(Coco Chanel)</strong>
          .col-sm-5.p-3
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta5/imagen1.svg')

        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estilo Bohemio
            p El estilo boho o bohemio, es un estilo originalmente popularizado por los bohemios en la década de los 60, un grupo de gente que rechazaba los valores morales tradicionales vivían un estilo de vida nómada. No solía ser considerado de moda por los estándares del momento. Originalmente se usaba por comodidad y para desafiar las normas de vestir tradicionales.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | El estilo bohemio es relajado, confortable y lo más importante, una expresión personal. 
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Valora la comodidad.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Las mujeres optan por vestidos sueltos, túnicas, faldas de volados y pantalones amplios o tipo gaucho.
            p.p-3(style='background-color: #FEF5E5') “No se puede tener un estilo bohemio usando prendas ajustadas; esto no funciona. Tiene que tener la posibilidad de moverse, bailar y escalar.”  <strong>(Diane Von Furstenberg)</strong>
          .col-sm-5.p-3
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta5/imagen2.svg')

        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estilo Minimalista
            p El concepto nació en los años sesenta, con la idea de “menos es más”, del arquitecto Mies Van Der Rohe, quien propuso un estilo de vida que rescata la importancia de la persona, frente a una sociedad consumista. A grandes rasgos, trata no sólo de usar poco, sino de encontrar el equilibrio entre reducir y exagerar en la decoración, los detalles y las siluetas.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | El estilo minimalista requiere de disciplina, consistencia y gran atención por la calidad.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | La mayoría de los minimalistas son metódicos en el momento de vestirse y tienen un gran sentido y conciencia de sí mismos.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Son muy fieles a algunas marcas que les garantizan cortes y diseños perfectos, telas de alta calidad y tecnológicas.
            p.p-3(style='background-color: #FEF5E5') “En el minimalismo no se trata de abandonar los diseños o los estampados. Yo veo al minimalismo como la filosofía que envuelve el total sentido del balance, conociendo cuándo quitar o sustraer algo. Es un vicio por los cortes absolutamente impecables, juegos tranquilos del color siluetas muy fuertes y limpias.”  <strong>(Calvin Klein)</strong>
          .col-sm-5.p-3
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta5/imagen3.svg')

        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estilo Street Fashion
            p Este estilo único y original se observa en las calles de todo el mundo, donde las personas adoptan la indumentaria de manera muy personal. Estas personas no siguen las tendencias de moda establecidas; por el contrario, son ellas quienes inspiran a los diseñadores a crear nuevas colecciones.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Es original y no sigue tendencias.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Crea su propia identidad y estilo.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Es rebelde.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Les interesa la autenticidad de cada persona, antes que lo que está de moda en el mercado.
          .col-sm-5.p-3
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta5/imagen4.svg')

        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estilo Ecléctico
            p Una persona ecléctica es aquella que selecciona sus prendas de todos los estilos y la mezcla de una manera única. No hay una fórmula ni elementos favoritos, es una invención permanente.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Es original y no sigue tendencias.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Mezclar prendas vintage elegidas con estilo individual.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Objetos antiguos elegidos con buen gusto y algo de audacia.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Se pueden incorporar objetos exóticos, prendas de otras décadas, accesorios de todo de todo tipo, como si se tratara de un collage.
          .col-sm-5.p-3
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta5/imagen5.svg')

        .row.p-5
          .col-md-7.mb-4.mb-md-0
            h3 Estilo Nostálgico
            p Es un estilo que vive del recuerdo, del pasado. Es romántico y tiene en su esencia toques vintage y colores pasteles y empolvados.
            p.mb-0 <strong>Características:</strong>
            ul.color-primario
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | El estilo nostálgico tiene la característica de exigir gran decoración la cual muchas veces llega a ser excesiva.
              li.mb-0 
                i.lista-ul__vineta.mb-0
                | Es femenino y romántico.
              li.mb-0
                i.lista-ul__vineta.mb-0
                | Las flores y los volúmenes se destacan.
          .col-sm-5.p-3
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta5/imagen6.svg')

    .row.mb-5.p-5
      .col-1
      .col-10
        .tarjeta.actividad.p-3.color-primario
          .row.justify-content-around.align-items-center      
            .col-1.justify-content-around.align-items-center
              figure
                img(src='@/assets/curso/temas/tema1/imagen8.png', alt='Modisto')
            .col-8.justify-content-around.align-items-center
              h3 Perfil y estilo del consumidor
              p Revisa el documento que pueden resultar útil para aprender más sobre el perfil y estilo del consumidor.
            .col-2.justify-content-around.align-items-center
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Descargar
                i.fas.fa-puzzle-piece

    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.4.  Tendencias
    .row.mb-0
      p Las tendencias se definen a través de una serie de formas visuales y características específicas que identifican un momento concreto; esta información determina el comportamiento de consumo. Las tendencias mueven las industrias, no solo la industria de la moda, si no las de consumo, servicios, incluso pensamiento.

    .row
      .col-6
        .bloque-texto-f.color-primario.pt-4.px-5.mb-5
          h3.text-regular.bloque-texto-f__texto(style='color: white') <strong>¿Qué es?</strong>
          h3.text-regular.bloque-texto-f__texto(style='color: white') Las tendencias buscan entender qué está pasando en el contexto mundial. "Tendencia" significa desarrollarse o cambiar en una dirección general. Es la predicción del estado de ánimo, comportamientos y hábitos del consumidor.
          .bloque-texto-f__avatar
            .bloque-texto-f__avatar__img
              img(src='@/assets/curso/temas/tema1/imagen9.png')
              .col-6
      .col-6
        .bloque-texto-f.color-acento-contenido.pt-4.px-5.mb-5
          h3.text-regular.bloque-texto-f__texto <strong>¿Quiénes?</strong>
          br
          h3.text-regular.bloque-texto-f__texto Un grupo de personas dedicadas a ser cazadores de tendencias, los llamados "coolhunter" detectar y predecir las novedades que vendrán en los campos de la moda y el consumo.
          .bloque-texto-f__avatar
            .bloque-texto-f__avatar__img
              img(src='@/assets/curso/temas/tema1/imagen10.png')

    .row
      .col-sm-2
      .col-sm-3.p-5(style='background-color: #FEF5E5')
          img(src='@/assets/curso/temas/tema1/imagen11.png')
      .col-sm-5.mb-5.mb-sm-2(style='background-color: #FEF5E5')
        br
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1
            | <strong>Ritmo:</strong> Forma en la que sucede y se alternan una serie de dinámicas, conceptos y sentires que componen la tendencia.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | <strong>Información:</strong> Toda la variedad de información que puedan complementar el concepto de la tendencia
          li 
            .lista-ol--cuadro__vineta
              span 3
            | <strong>Diversificación:</strong> Diferentes variables en donde se puede manifestarse la tendencia, sus conceptos, y historias.
          li 
            .lista-ol--cuadro__vineta
              span 4
            | <strong>Tecnología:</strong> Medios por los cuales se revela la información y su implementación.

    .row.mt-5
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ ¿Cómo identificar una tendencia?

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta6/imagen1.png')
          
        h2.text-center Metatendencias
        p “Una metatendencia significa un cambio multidimensional, por oposición a un cambio lineal o secuencial. Son los cambios sustanciales en nuestra estructura socioeconómica” (Blink Design – Laura Novik).
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta6/imagen2.png')
          
        h2.text-center Macrotendencias
        p Son las tendencias donde se involucran muchas áreas, sistemas productivos y aspectos emocionales.
      .col-md.tarjeta.color-acento-contenido.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/tarjeta6/imagen3.png')
          
        h2.text-center Microtendencias
        p Son las que dan origen a las llamadas “modas pasajeras”, cambian cada temporada, revolucionan el mercado, abren un abanico de posibilidades y promueven el consumo..

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ ¿Quiénes estudian las tendencias?

    .row.justify-content-center.mb-5
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/tarjeta9/imagen1.png")
          .crd_hover_txt--body
            h4.mb-3 INEXMODA
            p.mb-0 https://www.inexmoda.org.co/

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/tarjeta9/imagen2.png")
          .crd_hover_txt--body
            h4.mb-3 PREMIÉRE VISION PARIS 
            p.mb-0 https://www.premierevision.com/en/

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/tarjeta9/imagen3.png")
          .crd_hover_txt--body.p-5
            h4.mb-3 FASHION TRENDSETTER
            p.mb-0 https://www.fashiontrendsetter.com/v2/

    .row.justify-content-center.mb-5
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/tarjeta9/imagen4.png", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 FASHION SNOOP
            p.mb-0 https://www.fashionsnoops.com/

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/tarjeta9/imagen5.png", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 WGSN
            p.mb-0 https://www.wgsn.com/es/wgsn/

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/tarjeta9/imagen6.png", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 PECLERS PARIS
            p.mb-0 https://www.peclersparis.com/fr/

    .row.mt-5(style='background-color: #D1BCFF')
      .col-1
      .col-3.p-5 
        img(src='@/assets/curso/temas/tema1/signo-de-interrogacion.png')
      .col-7.p-5
        br
        p <strong>La clave es:</strong> identifiquemos los principales factores que afectan el pronóstico de las tendencias. <br>
        p <strong>Estaciones:</strong> las tendencias se basan en las estaciones de primavera (spring), verano (Summer), otoño (Autumn) e invierno (Winter). 

    .row.mb-4.p-5
      .col-1
      .col-10
        .tarjeta.actividad.p-3.color-primario
          .row.justify-content-around.align-items-center      
            .col-1.justify-content-around.align-items-center
              figure
                img(src='@/assets/curso/temas/tema1/revista.png')
            .col-8.justify-content-around.align-items-center
              h3.mb-0 Tendencias
              p.mb-0 Revisa el documento que pueden resultar útil para aprender más sobre el entorno de las tendencias.
            .col-2.justify-content-around.align-items-center
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Descargar
                i.fas.fa-puzzle-piece

    .row.mb-4
      .titulo-segundo.color-primario
        h2 1.5.  <em>Moodboard</em> - <strong>Cuadro metamórfico</strong>

    .row.mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Nota. Adaptado de Perfil y estilo de consumidor.
    .row.mb-4
      p Los moodboards son tableros creativos que permiten visualizar y conceptualizar ideas para el desarrollo de productos o servicios, consiste en recolectar imágenes que muestran lo que se quiere expresar, esta es una forma implementada en las áreas de diseño para dar a conocer las ideas de una manera mucho más dinámica.

    .row.justify-content-center.align-items-center
      .col-lg-10
        .row.justify-content-center.mb-5
          .col-lg-7        
            .row.p-4.align-items-center.borde-redondo.color-morado-claro
              h3 ¿Qué es un <em>moodboard?</em>
              p Como su nombre lo indica, es un tablero de inspiración visual que logra conectar las ideas en un solo espacio por medio visual o físico. Reúne imágenes, colores, texturas, frases... con la intención de hacer tangible un concepto o un ambiente.
            .row.p-4.align-items-center.borde-redondo.color-morado-fuerte
              h3.text-white ¿Para qué sirve?
              p.text-white Para generar una inspiración conceptual donde se plasman sentimientos o estados de ánimo que desean evocar.
            .row.p-4.align-items-center.borde-redondo.color-morado-claro
              h3 ¿Cómo se hace?
              p.mb-0 <strong>Físico:</strong> recortes de revista, texturas, elementos.
              p.mb-0 <strong>Digital:</strong> imágenes digitales, complementos.
          .col-lg-4.p-2.mt-5
              img(src="@/assets/curso/temas/tema1/imagen14.svg", alt="alt")


    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ Proceso para desarrollar un <em>moodboard</em>
    
    .row.mb-4
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-acento-contenido.p-5
          .tarjeta-numerada__numero
            .h2 1
          p.text-center 
            h3.text-center Palabras claves
          p.text-center Defina las palabras esenciales, frases y/o conceptos.
          br
          br
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-primario.p-5
          .tarjeta-numerada__numero
            .h2 2
          p.text-center 
            h3.text-center Imágenes
          p.text-center Realice un banco de imágenes acorde a los conceptos, referentes, paleta de color y demás.
          br
      .col-md-6.col-xl.mb-4.mb-xl-0
        .tarjeta-numerada.color-acento-contenido.p-5
          .tarjeta-numerada__numero
            .h2 3
          p.text-center 
            h3.text-center Diagramación
          p.text-center Empiece con la diagramación en su moodboard, puede hacerlo lineal o abstracto. Herramientas: Canva – PowerPoint.

    .row
      .titulo-segundo.color-acento-contenido
        h3(style="color: #673AB7") \\\ ¿Qué es un cuadro metamórfico?
    .row
      p Es una metodología de diseño que permite mostrar fácilmente un concepto definido y que se vea reflejado armónicamente en los productos realizados. Metodología tomada del diseño industrial.

    TabsA.color-acento-botones
      .tarjeta.p-4(titulo="¿Para qué sirve?" style='background-color: #FEF5E5')
        h4 ¿Para qué sirve?
        .row
          .col-xl-9
            p Esta metodología permite lograr variedad de diseños rápidamente, facilita la realización de evoluciones y modificaciones de diseño en una colección sin que se pierda la coherencia conceptual.
          .col-2.mb-0
              img(src='@/assets/curso/temas/tema1/tarjeta8/imagen1.png')

      .tarjeta.p-4(titulo="¿Cómo iniciar?" style='background-color: #FEF5E5')
        h4 ¿Cómo iniciar?
        .row
          .col-xl-9
            p <strong>Tipologías:</strong> elegir las tipologías a trabajar.
            p <strong>Siluetas:</strong> definir el tipo de silueta de la prenda.
            p <strong>Visualizar</strong> partes de las prendas por separado: cuellos, bolsillos, mangas, escotes, sistema de cierre, sistema de ajuste.
          .col-2.mb-0
              img(src='@/assets/curso/temas/tema1/tarjeta8/imagen2.png')

      .tarjeta.p-4(titulo="¿Cómo se realiza?" style='background-color: #FEF5E5')
        h4 ¿Cómo se realiza?
        .row
          .col-xl-9
            p Se organizan las ideas utilizando un esquema tipo tabla; para generar varias opciones de cada una de esas partes (estas siempre deben comunicar el concepto de la marca).
          .col-2.mb-0
              img(src='@/assets/curso/temas/tema1/tarjeta8/imagen3.png')

    .row.mt-5(style='background-color: #D1BCFF')
      .col-1
      .col-3.p-5 
        img(src='@/assets/curso/temas/tema1/signo-de-interrogacion.png')
      .col-7.p-5
        br
        p <strong>La clave es:</strong> identifiquemos los principales factores que afectan el pronóstico de las tendencias. <br>
        p <strong>Estaciones:</strong>  las tendencias se basan en las estaciones de primavera (spring), verano (Summer), otoño (Autumn) e invierno (Winter).  

    .row.mt-5(style='background-color: #FFEBAB')
      .col-1
      .col-3.p-5 
        img(src='@/assets/curso/temas/tema1/signo-de-admiracion.png')
      .col-7.p-5
        br
        p <strong>Ejemplo:</strong>
        p ¿Cómo hacer que las variaciones basadas en un moodboard sean coherentes con un concepto? <br>
        p <strong>Nota:</strong>  todo el texto, tiene imágenes visuales de ref. Las cuales complementan la información entregada - anexar imágenes ppt de referencia.  

    .row.mb-4.p-5
      .col-1
      .col-10
        .tarjeta.actividad.p-3.color-primario
          .row.justify-content-around.align-items-center      
            .col-1.justify-content-around.align-items-center
              figure
                img(src='@/assets/curso/temas/tema1/imagen13.png')
            .col-8.justify-content-around.align-items-center
              h3.mb-0 <em>Moodboard</em> Tableros Creativos y Cuadro Metamórfico 
              p.mb-0 Revisa el documento que pueden resultar útil  para aprender más sobre la creación de un moodboard y un cuadro metamórfico.
            .col-2.justify-content-around.align-items-center
              a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                span Descargar
                i.fas.fa-puzzle-piece
      
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
