<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span.text-dark 4
      h1 Experiencias turísticas
    .row.justify-content-center.ampliarambos.fondo42
      .col-xxl-12.px-5
        .row.justify-content-center
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-right")
            img.mt-4(src='@/assets/curso/tema2/imagen1.jpg')
          .col-xxl-6.col-xl-6.col-lg-6.col-md-8.col-sm-11.col-11(data-aos="fade-up-left")
            .cajon.puntacajon3.p-4.mb-4.fondo43.mt-4.sombracajon
              p Lo interesante de viajar no solo es adquirir bienes y servicios, sino “vivir una experiencia” que aporte novedad y genere un sentido de autorrealización y autodesarrollo. Todos los actores del sistema turístico tienen la responsabilidad de hacer que los viajeros se lleven una buena imagen del lugar, a partir de las sensaciones y emociones que puedan generar en ellos y que puedan ser replicadas posteriormente a través de su voz a voz.
            p Dentro de los bienes o productos que normalmente se adquieren en un viaje, se podrían mencionar por ejemplo los <i>souvenirs</i>; entre los servicios, se puede hablar por ejemplo del transporte; y entre las experiencias, “aquellas que permiten vivenciar una realidad distinta, como, por ejemplo, una cultura ajena a la nuestra” (Sernatur, 2017). 
            p Una experiencia turística, por tanto, es el conjunto de emociones y sensaciones y que el turista obtiene durante todas las fases de contacto con el producto turístico. 
          p.my-5 Ofrecer experiencias de calidad es un factor indispensable para ser competitivo en el sector turístico y para orientarse hacia las necesidades del público objetivo, ahorrando de esa manera los costos e inversiones innecesarias que dejen por fuera nuestro nicho de valor estratégico.
         

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
