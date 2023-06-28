<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mt-3(data-aos="fade-up") El futuro tecnólogo en desarrollo de productos electrónicos interpretará el funcionamiento de los mismos a través de diagramas de bloques de circuitos y equipos, por medio de manuales técnicos de componentes, equipos y otros elementos accesorios.  Estará en capacidad de reconocer características técnicas de los productos electrónicos, teniendo en cuenta los sistemas y subsistemas propios de la tecnología.  
    p.mt-3(data-aos="fade-up") Con el conocimiento del presente componente formativo, el egresado podrá realizar servicio posventa, de acuerdo con protocolos de atención al cliente y normativas de calidad de la empresa y otras generales.

    .col.lg-12.col-lg-10.offset-lg-1 
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/introduccion/1.jpg')})`}"
        )
        .bloque-texto-g__texto.p-4.mt-3
          p.mb-0(data-aos="fade-up") También le permitirá conocer la terminología del mantenimiento electrónico, teorías para configurarlo, gráficas para revisarlo, analizar los resultados y corregir los problemas que se presenten o puedan presentarse. Todo lo anterior con el fin de aplicar controles posteriormente al plan de mantenimiento, de acuerdo con su clasificación.
          br
          br
    p.mt-3(data-aos="fade-left") Finalmente, conocerá los tipos de equipos electrónicos que existen en el mercado para visualizar los objetivos del negocio o del mantenimiento para los mismos.
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
