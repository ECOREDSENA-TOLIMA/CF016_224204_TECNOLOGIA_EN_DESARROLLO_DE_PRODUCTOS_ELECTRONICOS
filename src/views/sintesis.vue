<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p.mb-5 La gestión del mantenimiento de equipos electrónicos es un proceso clave en la planificación y operación de cualquier empresa que utilice tecnología electrónica. Para ello, se utilizan diferentes tipos de mantenimiento, como el preventivo, correctivo, predictivo y proactivo, así como herramientas como diagramas de procesos, flujo y Pareto. Es importante clasificar los equipos electrónicos según su línea, como la blanca, gris y marrón, para facilitar su mantenimiento y servicio al cliente. Además, es necesario tener conocimientos sobre energía eléctrica, diodos, transistores, circuitos integrados y tarjetas de circuitos impresos. Por último, es fundamental tener protocolos y normativas de calidad para ofrecer un servicio posventa de calidad y atención al cliente efectivo.
    
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
