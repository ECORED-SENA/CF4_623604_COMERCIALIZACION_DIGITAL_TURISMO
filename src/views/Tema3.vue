<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span(style="color: #161730") 3
      h1 Competencia
    .row.justify-content-center
      .col-xxl-12.px-5
        .row.justify-content-center
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-right").m-4
            img.mt-4(src='@/assets/curso/tema3/img01.png')
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-left")
            p Hasta el momento se ha realizado el análisis de la empresa o emprendimiento a nivel interno y externo; #[span.etiqueta se ha podido determinar fortalezas, debilidades, amenazas y oportunidades, y se ha complementado este análisis con la comprensión de nuestro producto o servicio y del cliente ideal para él]. Pero sería lógico suponer que quizás no se esté solo en el mercado. 
            p Así que ha llegado el momento de analizar la competencia, ya que al elaborar el plan de mercadeo no se encontrará completo sin este componente. 
            .cajon.color-secundario.p-4.mb-4.mt-4.fondo1
              p Para iniciar esta exploración se puede mencionar que etimológicamente la palabra competencia proviene del latín <em>“competentia”</em>, que es la cualidad del que lucha para conseguir un premio y que según la Real Academia de la Lengua Española se define como la “situación de empresas que rivalizan en un mercado, ofreciendo o demandando un mismo producto o servicio.” 
    p.mb-0 #[span.etiqueta Partiendo de estos conceptos] se puede avanzar en conocer a sus competidores.
    p De aquí en adelante se van a seguir unos sencillos pasos que permitirán identificar y analizar su competencia y no fallar en esta importante etapa.
    separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.1 ¿Quiénes son mis competidores? 
    .row.justify-content-center
      .col-xxl-12.px-5
        .row.justify-content-center.align-items-center
          .col-xxl-3.col-lg-4.col-md-5.col-9.mb-4.bg3.p-3
            p.mb-3 En este aparte del plan de mercadeo se va a ubicar todas las empresas que operan en un mismo mercado (geográficamente hablando) y sector (se hace referencia al sector empresarial, aquí podría haber más de uno), ofreciendo un mismo producto o servicio. Estas empresas rivalizan entre sí, (nuestra empresa incluida) para obtener la preferencia de compra del cliente final a través de estrategias empresariales diferenciadas. Por lo tanto, se debe hacer una correcta identificación de ellos, por así decirlo debe dársele un nombre y apellido.
          .col-xxl-3.col-lg-4.col-md-5.col-9.mb-4.d-flex.align-items-center
            img(src="@/assets/curso/tema3/img02.png")
          .col-xxl-3.col-lg-4.col-md-5.col-9.mb-4.bg4.p-3
            p Luego de tener un listado preliminar se puede determinar cómo afectan nuestra cuota de mercado, quienes son sus clientes, cuáles son sus precios medios, la posición competitiva, mapas de localización y todos los datos primarios que se consideren importantes.
            p Para organizarlos se puede hacer en tres tipos genéricos de competidores que la industria ha determinado, tal como se observa en el siguiente recurso educativo:
    TabsC.color-primario(data-aos="fade-up-left").mb-5
      .py-3.py-md-4(titulo="Competidores directos o de primer grado")
        .row.justify-content-around
          .col-md-8.mb-4.mb-md-0
            p Son aquellas empresas que:
            ul.lista-ul--color
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Operan en nuestro mismo mercado. 
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Canales de distribución idénticos. 
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Atienden al mismo perfil de potenciales clientes y cubren las mismas necesidades.  
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Servicios o productos iguales o parecidos.
            p Para ejemplificar en el campo hotelero, para #[em Hilton], su competencia directa es #[em Marriott].
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/img03.svg', alt='Texto que describa la imagen')
      .py-3.py-md-4(titulo="Competidores indirectos o de segundo grado")
        .row.justify-content-around
          .col-md-8.mb-4.mb-md-0
            p Son aquellas empresas que:
            ul.lista-ul--color
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Operan en el mismo mercado. 
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Canales de distribución iguales. 
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Atienden el mismo perfil de potenciales clientes y cubren las mismas necesidades.   
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Producto o servicio difiere en alguno de sus atributos principales.
            p Para seguir con el mismo ejemplo Coca-Cola, en este caso su competencia indirecta podrían ser otros hoteles, como GHL, Estelar.
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/img04.svg', alt='Texto que describa la imagen')
      .py-3.py-md-4(titulo="Productos sustitutos o competidores de tercer grado")
        .row.justify-content-around
          .col-md-8.mb-4.mb-md-0
            p Son empresas que:
            ul.lista-ul--color
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Operan en el mismo mercado y sector.
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Canales de distribución idénticos.
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | Atienden el mismo perfil de potenciales clientes y cubren las mismas necesidades.   
              li 
                i.fa.fa-dot-circle(style="color: #FF854E")
                | El producto o servicio es otro, pero satisface la misma necesidad del nuestro.
            p En el caso de los hoteles, los productos sustitutos podrían ser cualquier servicio de alojamiento alterno como AirBNB.
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/img05.svg', alt='Texto que describa la imagen')
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-10.p-2.px-2.bg6
        p.text-center Es recomendable analizar al menos dos y si es posible las tres opciones de competencia que se han indicado.
    separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.2 Niveles de análisis de la competencia
    .bloque-texto-g.bg7.p-3.p-sm-4.p-md-5.my-5.otrobloque2(data-aos="fade-up-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img06.png')})`}"
      )
      .bloque-texto-g__texto.py-5.px-4
        p Genéricamente un mercado es un lugar teórico donde se encuentran la oferta y la demanda de productos y servicios. Al referirse a un lugar, el mercado tiene unos límites geográficos que en virtud de su amplitud crean diferentes niveles de análisis para los componentes del <em>marketing mix</em>. Estos niveles son:
    .row.justify-content-center.align-items-center.mb-5
      .col-xxl-6.col-xl-6.col-lg-5.col-md-8.col-sm-11.col-11(data-aos="fade-up-left")
        img(src='@/assets/curso/tema3/img07.svg')
      .col-xxl-6.col-xl-6.col-lg-7.col-md-11.col-sm-11.col-11(data-aos="fade-up-right")
        AcordionA.otroacordion2(tipo="b" clase-tarjeta="tarjeta tarjeta--azul1")
          .row(titulo="Nivel internacional")
            .col-md-11
              p Este análisis dependerá de si nuestra empresa opera o no a este nivel. O de si hay proyección de operar en él a futuro. Esto dará una visión macro de grandes empresas, con pautas e indicadores orientativos.
          .row(titulo="Nivel nacional")
            .col-md-11
              p Tendrá la radiografía de las empresas competidoras en el mercado nacional. Cómo operan, cuál es su volumen de ventas, los precios medios, la inversión en publicidad.
          .row(titulo="Nivel regional")
            .col-md-11
              p Debe entender cómo funciona y opera su competencia a este nivel. Sera útil analizar y valorar cifras y datos que, por ejemplo, podrá comparar con las cifras del negocio. Y saber si el aumento de las ventas ha sido mayor o menor al de sus competidores.
          .row(titulo="Nivel local")
            .col-md-11
              p Por ejemplo, la empresa es una tienda de barrio. Analizar y valorar cifras de los competidores más cercanos para poder establecer un plan de acción, de choque o de lanzamiento.
          .row(titulo="Nivel <em>online</em>")
            .col-md-11
              p Este es un nivel en el que debe conducir un análisis focalizado en el ámbito <em>web</em>, plataformas, <em>eCommerce</em>, redes sociales.
    .row.justify-content-center
      .col-xxl-12.px-5
        .row.justify-content-center.align-items-center
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-left")
            p Este análisis reviste un cierto grado de complejidad, sobre todo porque hay que tener en cuenta que hoy en día la presencia <em>online</em> podría llevar a una empresa local a tener presencia internacional. 
            p De una u otra manera la presencia <em>online</em> rompe las barreras físicas y otorga acceso a muchos mercados, a los que quizá antes no era posible acceder. Esto debe tenerse en cuenta según el producto y la naturaleza del negocio.
            .cajon.puntacajon.p-4.mb-4.bg3.sombracajon
              p A manera de ejemplo, el turismo es una industria que, aunque se ubica localmente, a través de la presencia <em>online</em> tiene posibilidad de vender sus servicios a nivel internacional.
              p Por esta razón, quizá un destino o empresa en particular tenga sus competidores, no a la vuelta de la esquina o en la misma ciudad, sino a varios miles de kilómetros. 
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-right")
            img.mt-4(src='@/assets/curso/tema3/img08.png').mb-4
    p.mb-0 Al final la recomendación es que en virtud del tamaño y lugar de operación de la empresa o emprendimiento se cubran el número de niveles de competencia que corresponda.
    separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.3 ¿Cómo llevar a cabo el análisis de la competencia?
    .row.fondo11.ampliarambos.py-5
      .col-xxl-6.col-xl-6.col-lg-7.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-right")
        p.mb-4 A la hora de realizar el análisis de la competencia los pasos son: 
        ul.lista-ul--color
          li
            i.fas.fa-check(style="color: #ED7D41")
            | Establecer un objetivo.
          li
            i.fas.fa-check(style="color: #ED7D41")
            | Determinar el tipo de competidor y el nivel de análisis.
          li
            i.fas.fa-check(style="color: #ED7D41")
            | Elegir entre 5 y 10 empresas. Las que se estimen más representativas. 
          li
            i.fas.fa-check(style="color: #ED7D41")
            | Extraer las variables de análisis.   
          li
            i.fas.fa-check(style="color: #ED7D41")
            | Realizar un estudio comparativo entre ellas.    
          li
            i.fas.fa-check(style="color: #ED7D41")
            | Luego comparar con los resultados de la empresa.      
      .col-xxl-6.col-xl-6.col-lg-5.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-left")
        img(src='@/assets/curso/tema3/img10.png')
    .row.justify-content-around.align-items-center(data-aos="fade-up-left")
      .col-xxl-12.col-xl-12.col-12.col-md-11
        .tarjeta.bg9.p-3.mb-5
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-3
              img(src="@/assets/curso/tema3/img22.svg")
            .col-lg-8
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  .titulo-segundo.color-acento-contenido
                    h2 Análisis de competencia
                  p Los indicadores más relevantes para realizar el análisis de competencias se indican en el siguiente recurso educativo que le permitirá una mejor comprensión:
              .col-sm-auto
                a.boton.color-primario.texto-dark(:href="obtenerLink('downloads/anexo2.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download
    .row.justify-content-around.align-items-center(data-aos="fade-up-left")
      .col-xxl-10.col-xl-10.col-11.col-md-11
        .tarjeta.bg8.p-3.mb-5
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/img11.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Para una mejor comprensión del tema en el anexo Análisis de competencia encontrará los resultados que se han consignado en un matriz comparativa.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('downloads/anexo1.xlsx')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    
    separador
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.4 Competencia imperfecta
    p Se conoce con este término la situación de mercado en la que los vendedores individuales (empresas) tienen la capacidad de influir sobre el precio de mercado de sus productos o servicios. Para que esta situación se dé normalmente se presentan barreras de entrada (restricciones legales) y unas marcadas diferencias en costos de funcionamiento y operación (pueden ser de inversión inicial o costes bajos de producción por economías de escala).
    p.mb-5 #[span.etiqueta #[b Los tipos de estructuras]] que tienen la competencia imperfecta se presentan a continuación.
    .titulo-sexto.color-acento-contenido
      h5 Tabla 2. 
      span <em>Tipos de estructuras de la competencia imperfecta</em>
    .tabla-a.color-primario.mb-5(data-aos="fade-up-left")
      
        thead
          tr(style="background-color: #3D672F")
            th.text-white Estructura de mercado
            th.text-white Número de oferentes y diferenciación
            th.text-white Grado de control, sobre el precio
            th.text-white Ejemplo  
        tbody
          tr.fonta
            th.text-center Monopolio
            td Una empresa dominante, sin productos sustitutos
            td.text-center Total
            td.text-center Google
          tr
            th.text-center Oligopolio
            td Pocas empresas con productos homogéneos o diferenciados
            td.text-center Parcial
            td.text-center Celulares y tecnología
          tr.fonta
            th.text-center Competencia monopolística
            td Muchas empresas con productos diferenciados
            td.text-center Se presenta control si se logra una característica diferencial marcada
            td.text-center Sector comida rápida
    p Estos conceptos se explican con mayor profundidad en el documento anexo Capítulo 5 del libro Economía y turismo de Mochón.
    separador
    #t_3_5.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.5 <em>Benchmarking</em>, concepto, características y herramientas
    .row.justify-content-center
      .col-xxl-12.px-5
        .row.justify-content-center.align-items-center
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-right").mb-5
            img.mt-4(src='@/assets/curso/tema3/img13.png')
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-left")
            p El <em>benchmarking</em> o "evaluación comparativa" ocurre alrededor del mundo, en múltiples industrias y en la vida diaria. Seguramente cuando va a hacer una compra, antes de comprar, primero investiga un poco y compara los productos en cuanto a características, precio y calidad, esto en esencia es <em>benchmarking</em>. Esta disciplina es muy relevante en la industria turística, donde constituye la base de trabajo para la analítica de desempeño, el <em>business intelligence</em> y el <em>revenue management.</em>
            .cajon.color-secundario.p-4.mb-4.mt-4.fondo1
              p El <em>benchmarking</em> se puede definir como el proceso ordenado y sistemático de recopilar, crear, comparar y analizar indicadores clave de desempeño de su empresa en relación con la competencia. El proceso de <em>benchmarking</em> en la industria hotelera se basa en datos históricos y crea tendencias que ayudan a entender el mercado y el contexto en el que se opera.
            p Como se mencionó el <em>benchmarking</em> está presente en muchas industrias, pero se tomará la industria hotelera como marco de referencia para describir y entender sus características. Es oportuno mencionar que el referente mundial en <em>benchmarking</em> hotelero es la compañía STR (acrónimo de Smith Travel Research) que posee la base de datos históricos más completa del sector hotelero y como explican en su página <em>web</em> #[a(href="https://str.com/"  target='_blank') https://str.com] proporcionan datos confidenciales, precisos y aplicables, por medio de reportes integrales que permiten a los clientes elaborar estrategias y competir dentro de sus mercados.
    p.mb-4 Para contextualizar y resumir el <em>benchmarking</em> la siguiente figura ofrece una descripción de sus principales características.
    .row.ampliarambos.fondo12.mb-5
      .col-xxl-12
        .row.justify-content-center.align-items-center
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              h5 Figura 5. <em>Características del benchmarking</em>
          .col-lg-10.p-5
            img(src='@/assets/curso/tema3/img15.svg')
    .row.justify-content-center.align-items-center.fondo13.ampliarambos.mb-0.p-5
      .col-xxl-6.col-xl-6.col-lg-5.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-left").mb-4
        img(src='@/assets/curso/tema3/img17.png')
      .col-xxl-6.col-xl-6.col-lg-7.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-right")
        p.mb-3 Es claro que medir y comparar el desempeño es un factor relevante en cualquier empresa. Esto no es distinto en la industria turística, en ella los indicadores clave de desempeño se aplican en las mediciones de rendimiento en operación, comercialización y mercadeo. Ahora tomando como referencia el <em>benchmarking</em> de la industria hotelera para medir se puede decir que los indicadores clave de desempeño de la industria son:
        ul.lista-ul
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Índice de penetración de mercado - <span style="color:#EB6F2D!important; font-weight:bold;">MPI</span> <em>(Market Penetration Index)</em> o Índice de ocupación.
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Índice medio de precio - <span style="color:#EB6F2D!important; font-weight:bold;">ARI</span> <em>(Average Rate Index)</em> o Índice de tarifa promedio.
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Índice de ingreso generado - <span style="color:#EB6F2D!important; font-weight:bold;">RGI</span> <em>(Revenue Generation Index) o Indice de RevPar</em>.
      .col-xxl-6.col-xl-6.col-lg-7.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-right")
        p.mb-3 Estos índices se generan en la comparación del #[span.etiqueta #[b desempeño propio vs. el desempeño del set competitivo]] y referido a los tres indicadores clave del desempeño hotelero.
        ul.lista-ul
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Porcentaje de ocupación.
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Tarifa promedio (ADR).
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 <em>RevPar</em>.
        p.mb-3 La preocupación por medir y comparar resultados, como ya se mencionó es un hecho subyacente a todas las industrias. Y ahora que se está inmerso en un mundo regido por los datos, la siguiente pregunta que se debe contestar es qué herramienta se debe utilizar para este análisis. La respuesta no es sencilla, ya que como se mencionó, las comparativas y mediciones se aplican en todos los niveles de las industrias (operativo, comercial, y de mercadeo). 
        p.mb-4 Dicho esto, se puede mencionar que existen herramientas <em>(software)</em> que permiten captar, organizar y analizar datos a gran escala, que se podrían utilizar de acuerdo con la necesidad específica. Por ahora solo se menciona.
      .col-xxl-6.col-xl-6.col-lg-5.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-left")
        img(src='@/assets/curso/tema3/img18.png')
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.bg3.me-4.py-2.mb-5.mb-lg-0
        .row.align-items-center
          .col-lg-2
            img.tamimg(src='@/assets/curso/tema3/img19.svg', alt='Texto que describa la imagen')
          .col-lg-8.py-1
            p #[b En Marketing digital]: Google trends, Alexa, SEMRush
      .col-lg-5.bg3.me-5-py-5
        .row.align-items-center
          .col-lg-2
            img.tamimg(src='@/assets/curso/tema3/img19.svg', alt='Texto que describa la imagen')
          .col-lg-8.py-4
            p #[b En Hotelería]: <em>STAR (STAR Report)</em>
    .row.justify-content-around.align-items-center(data-aos="fade-up-left")
      .col-xxl-10.col-xl-10.col-11.col-md-11
        .tarjeta.bg6.p-3.mb-5
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/img17.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Para una mejor comprensión respecto al tema de  <em>Introducing dSTAR</em> se recomienda que consulte el siguiente video, en el que podrá aprender más sobre este tema, y lo encuentra en el siguiente enlace: 
                .col-lg-3
                  .mt-3
                    a.boton.me-3.indicador__container(
                      :href="('https://www.youtube.com/watch?v=NfUUQ5dir6c')"
                      target="_blank"
                      type="application/pdf"
                      @mouseover="mostrarIndicador = false"
                    )
                      span Ver video
                      i.fas.fa-play
                      .indicador--click(v-if="mostrarIndicador")
    separador
    #t_3_6.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.6 La segmentación de mercados 
    .row.justify-content-center.align-items-center.fondo13.ampliarambos.mb-5.p-5
      .col-xxl-6.col-xl-6.col-lg-7.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-right")
        p.mb-3 También conocida como segmentación de clientes o segmentación de audiencias #[span.etiqueta es un método por el cual se pueden dividir a los clientes potenciales en distintos grupos, los cuales permiten que las empresas puedan enviar mensajes personalizados a las audiencias correctas].
        p.mb-3 De manera general, segmentar es subdividir un mercado en subgrupos homogéneos de clientes, que demandan los mismos productos, tienen hábitos de compra similares y cumplen las siguientes condiciones:
        ul.lista-ul
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Que sea medible.
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Que sea accesible.
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Que sea significativo.
          li
            i.fas.fa-check(style="color: #ED7D41")
            p.mb-0 Que sea accionable.
      .col-xxl-6.col-xl-6.col-lg-5.col-md-11.col-sm-11.col-11.px-5(data-aos="fade-up-left")
        img(src='@/assets/curso/tema3/img20.png').mb-4
      p.mb-0 A continuación podrá encontrar cuáles son los 5 pasos para implementar una estrategia de segmentación de mercados, los cuales permiten acertar de manera precisa en la venta de productos en el mercado que sea de interés, según el producto que desea ofrecer:
    .row.justify-content-center.align-items-center.mb-5
      .col-xxl-6.col-lg-6.col-md-10.col-sm-11.col-11.mb-5.mb-md-0(data-aos="fade-up-left")
        img.mt-4(src='@/assets/curso/tema3/img21.png')
      .col-xxl-6.col-lg-6.col-md-10.col-sm-11.col-11.mb-5.mb-md-0(data-aos="fade-up-left")
        LineaTiempoD
          p(numero="1" titulo="Defina su mercado") En este punto de la segmentación de mercados debe enfocarse en descubrir qué tan grande es el mercado, dónde encaja su marca y si sus productos tienen la capacidad de solucionar lo que promete.
          p(numero="2" titulo="Segmente  su mercado") Este paso consiste en elegir cuál de los tipos de segmentación de mercado es el que más se adecua a su marca.
          p(numero="3" titulo="Comprenda su mercado") Realice a sus clientes las preguntas adecuadas, dependiendo del tipo de segmentación de mercados que eligió. Debe conocer a su público objetivo detalladamente. Puede utilizar encuestas <em>online</em> para obtener sus respuestas.
          p(numero="4" titulo="Construya su segmento de clientes") Después de recolectar las respuestas, es necesario realizar un análisis de datos para crear segmentos dinámicos únicos para su marca.
          p(numero="5" titulo="Ponga a prueba su estrategia") Asegúrese de haber interpretado correctamente los datos de su encuesta, poniéndolos a prueba con su público objetivo. Esto le ayudará a revisar nuevamente sus estrategias de segmentación de mercados y hacer los cambios necesarios. 
    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-secundario.p-4.mb-5.fondo1
          .row.align-items-center
            .col-lg-auto.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema3/img20.svg' style="width: 90px").m-auto
            .col
              p.mb-0 En síntesis, la segmentación del mercado debe permitir clasificar y entender a los diferentes tipos de clientes, determinando sus necesidades y motivaciones puntuales, para poder crear propuestas de valor específicas para cada grupo significativo y medir sus resultados en forma desagregada en pos del resultado final.


    
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
