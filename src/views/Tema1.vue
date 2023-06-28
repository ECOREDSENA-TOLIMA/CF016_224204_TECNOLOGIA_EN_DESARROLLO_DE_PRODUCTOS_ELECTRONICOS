<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Mantenimiento de equipos electrónicos
    p.mt-3(data-aos="fade-left") En el mantenimiento de equipos electrónicos, se conocen dos categorías: el mantenimiento preventivo y el correctivo, ambos tienen el objetivo de preservar el funcionamiento del sistema o dispositivo cualquiera que sea su función.  En la siguiente figura, se observa cómo la planeación se enfoca en el mantenimiento preventivo.
    .row
      .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 1.</b> <i>Plan de mantenimiento</i>
    .row   
      .col-sm-12.mb-3.col-lg-10.offset-lg-1.mt-3(data-aos="zoom-in-up")
        figure
          img(src='@/assets/curso/temas/tema1/1.svg', alt='')

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-12
          .row.justify-content-center.align-items-center
            .col-12.px-0(data-aos="fade-left")
              .cajon.color-primario
                .row.justify-content-center.align-items-center.py-0.mt-1
                  .col-12.mt-4.mb-4.px-5
                    p.mb-lg-0.lg-mb-5 En algunas empresas, también se utilizan los mantenimientos predictivos y proactivos.

    p.mt-3(data-aos="fade-left") Ahora bien, dentro de este proceso, se deben tener presentes determinados diagramas.

    .col.lg-12.col-lg-10.offset-lg-1 
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/2.jpg')})`}"
        )
        .bloque-texto-g__texto.p-4.mt-3
          p.mb-0(data-aos="fade-up") Un diagrama es un gráfico de complejidad baja o alta, con diferentes cantidades de elementos según la complejidad, para facilitar la transmisión de la información del proceso en sí.
          br
          br
          br
          br
    p.mt-3(data-aos="fade-up") El uso de diagramas de procesos es muy importante para el desarrollo del mantenimiento, pues ayuda a la visualización de los pasos, las acciones a realizar en cada uno, los controles de calidad del proceso, la retroalimentación y fin del mismo.   
    p.mt-3(data-aos="fade-up") El uso del diagrama de procesos ayuda a que este sea utilizado de manera teórico – visual, enfocado a que el desarrollo del plan de mantenimiento, preventivo o correctivo, se ejecute de manera adecuada, en vez de efectuarlo a través de una lista de chequeo. Estos gráficos contribuyen además a ser una ayuda de memoria visual. Dentro de ellos, se encuentran: el diagrama de flujo y el diagrama de Pareto.


    TabsA.color-primario
      .tarjeta.color-primario--borde.p-4(titulo="Diagrama de flujos")
        p Es una parte a priori del diagrama de procesos.  El diagrama de flujos es el más utilizado y conocido en las diferentes áreas de operación de la fabricación electrónica y especialmente en la producción y en el mantenimiento. Son bastante usados por la tecnología y se caracterizan porque:
        ul.lista-ul.mb-3.mt-3
          li 
            i.lista-ul__vineta
            | Tienen un óvalo como punto de partida y de cierre.
          li 
            i.lista-ul__vineta
            | Un rectángulo, para indicar acciones.
          li 
            i.lista-ul__vineta
            | El rombo se usa para definir la ejecución de una toma de decisión.
          li 
            i.lista-ul__vineta
            | Los círculos, como componentes conectores. 
          li 
            i.lista-ul__vineta
            | Los triángulos, para mostrar los archivos o documentos relacionados.  
        p El diagrama de flujo muestra gráficamente los pasos o etapas de un proceso.  También recibe el nombre de flujograma o diagrama de actividades.
        .row
          .titulo-sexto.color-primario.mb-0.offset-lg-3(data-aos="fade-left")
            p.titulo.pb-0.mb-0 <b>Figura 2.</b> <i> Diagrama de flujo</i>
        .row   
          .col-sm-12.mb-3.col-lg-10.offset-lg-1.mt-3(data-aos="zoom-in-up")
            figure
              img(src='@/assets/curso/temas/tema1/3.svg', alt='')
              figcaption Nota. Tomado de Huerta (2014). 

      .tarjeta.color-primario--borde.p-4(titulo="Diagrama de Pareto")
        p Es un gráfico de barras que ordena las frecuencias de mayor a menor, permitiendo la priorización de los problemas. Muestra la curva de porcentajes acumulados. Se utiliza mucho para observar problemas y buscar la solución a ellos mediante el análisis de la gráfica.  
        p El diagrama de Pareto se basa en el Principio de Pareto, el cual es una herramienta que posibilita la identificación de lo importante y lo no importante. La figura puede mostrar los problemas en la manufacturación de las tarjetas de circuitos impresos comparados con los defectos de la producción en general. Con la curva acumulada, se pueden observar las causas de mayor incidencia en el problema.
        .row
          .titulo-sexto.color-primario.mb-0.offset-lg-3(data-aos="fade-left")
            p.titulo.pb-0.mb-0 <b>Figura 3.</b> <i>Diagrama de Pareto aplicado a problemas de producción</i>
        .row   
          .col-sm-12.mb-3.col-lg-10.offset-lg-1.mt-3(data-aos="zoom-in-up")
            figure
              img(src='@/assets/curso/temas/tema1/4.svg', alt='')
              figcaption Nota. Calidad & Gestión (s. f.).  
    
    p.mt-5(data-aos="fade-up") El procedimiento para diseñar un diagrama de Pareto se puede resumir de la siguiente forma.
    .row
      .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3.mt-3(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 4.</b> <i>Pasos para un diagrama de Pareto</i>
    .row   
      .col-sm-12.mb-3.col-lg-10.offset-lg-1.mt-3(data-aos="zoom-in-up")
        figure
          img(src='@/assets/curso/temas/tema1/5.svg', alt='')

    
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
