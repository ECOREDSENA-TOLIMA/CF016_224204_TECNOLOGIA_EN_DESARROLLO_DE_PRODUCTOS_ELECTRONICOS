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
        p Tienen un óvalo como punto de partida y de cierre.
        p Un rectángulo, para indicar acciones.
        p El rombo se usa para definir la ejecución de una toma de decisión.
        p Los círculos, como componentes conectores. 
        p Los triángulos, para mostrar los archivos o documentos relacionados.  
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

    p.mt-3(data-aos="fade-up") Los equipos electro-electrónicos están fundamentados en la energía mediante la cual se alimentan, esto es, la energía eléctrica y, por tanto, su funcionamiento es electrónico. La electrónica, por su parte, inició con los diodos, tipo tubos de vacío, y se transformó con la creación del transistor.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-12
          .row.justify-content-center.align-items-center
            .col-12.px-0(data-aos="fade-left")
              .cajon.color-primario
                .row.justify-content-center.align-items-center.py-0.mt-1
                  .col-12.mt-4.mb-4.px-5
                    p.mb-lg-0.lg-mb-5 Actualmente, todos los equipos que se utilizan son electro-electrónicos, porque su fuente de alimentación es la energía eléctrica y su configuración es electrónica, con miles de transistores agrupados en tarjetas de circuitos impresos y circuitos integrados.  

    p.mt-3(data-aos="fade-up") La siguiente figura expone cómo, sin importar el lugar, usted está rodeado de estos equipos, mediante algunos ejemplos de contexto específicos.


    .row.justify-content-center.align-items-center
      .col-lg-4.col-12(data-aos="zoom-out-right")
        figure
          img(src='@/assets/curso/temas/tema1/6.svg', alt='')
      .col-8.px-0(data-aos="fade-up")
        .tarjeta.color-primario.p-4
          h4 Hogar
          p Equipos utilizados en el hogar para la diversión, como el televisor, reproductores de audio y video, juegos y la radio misma, son equipos electro-electrónicos; en la cocina y otras áreas del hogar, encontramos equipos de iguales características. 
      .col-lg-4.col-12(data-aos="zoom-out-right")
        figure
          img(src='@/assets/curso/temas/tema1/7.svg', alt='')
      .col-8.px-0(data-aos="fade-up")
        .tarjeta.color-primario.p-4
          h4 Oficina
          p Existe un sinnúmero de equipos electro-electrónicos que cumplen esas propiedades, como el computador, el teléfono, la impresora, elementos de las redes LAN y/o  WIFI, conmutador, y otros como la cortadora de papel, la fotocopiadora y copiadora digital (scanner). 
      .col-lg-4.col-12(data-aos="zoom-out-right")
        figure
          img(src='@/assets/curso/temas/tema1/8.svg', alt='')
      .col-8.px-0(data-aos="fade-up")
        .tarjeta.color-primario.p-4
          h4 Industria
          p Si se explora la industria, y en el mismo mantenimiento, se encuentran equipos electro-electrónicos, como los osciladores, generadores de frecuencia, multímetros y muchas máquinas más, incluidas las máquinas CAD/CAM para trabajar las tarjetas de circuitos impresos.

    .col-12.mt-4
      p(data-aos="zoom-in") Existen varias clasificaciones de los equipos electrónicos, como son la línea blanca, dividida en grandes y pequeños electrodomésticos, línea gris, línea marrón, y otros equipos electrónicos, herramientas, juguetes, equipos médicos, instrumentos de vigilancia y máquinas. 
      p(data-aos="zoom-in") Los equipos electrónicos son considerados en varias categorías que podrá ver a continuación, y de acuerdo con las mismas, son clasificados; para algunos de ellos se aplica una clasificación común.
      p(data-aos="zoom-in") Esta categorización de los aparatos eléctricos y electrónicos (AEE) en la UE se da según la Directiva RAEE de 2002 del Parlamento Europeo y el Consejo de la Unión Europea (2003), adaptación del Ministerio de Ambiente y Desarrollo Sostenible de Colombia (2017).

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10.col-12.mb-4
        .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
          p.titulo.pb-0.mb-0 <b>Figura 6.</b> <i>Categorización equipos electro-electrónicos</i>
      .col-lg-8.col-12.mb-5(data-aos="zoom-out-right")
        figure
          img(src='@/assets/curso/temas/tema1/9.png', alt='')
    
    .col-12.mt-4
      p(data-aos="zoom-in") A continuación, se explica un poco más acerca de algunos de ellos.

    .row.justify-content-center.align-items-center.mt-5
      AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
        .row(titulo="Grandes electrodomésticos")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Los grandes electrodomésticos son fabricados especialmente para uso en el hogar y, sin embargo, varios de ellos son utilizados en el comercio y en la industria especializada, como lavanderías, servicio médico, gastronomía y panadería, investigación.  En esta categoría, según la norma, se encuentran: 
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 1.</b> <i>Categorización equipos electro-electrónicos</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/10.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Los grandes electrodomésticos son fabricados especialmente para uso en el hogar y, sin embargo, varios de ellos son utilizados en el comercio y en la industria especializada, como lavanderías, servicio médico, gastronomía y panadería, investigación.  En esta categoría, según la norma, se encuentran:        
            p(data-aos="zoom-in") Los grandes electrodomésticos actualmente utilizan tarjetas de circuitos impresos para control electrónico en su operación y mantenimiento, varios de ellos tienen la opción de conectarse a Internet a través de la metodología Internet de las cosas.

        .row(titulo="Pequeños electrodomésticos")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Los pequeños electrodomésticos son fabricados para la higiene de las personas, ciertas actividades del hogar, como cocinar, cuidar y limpiar la ropa y la casa, además, para la comodidad de las personas. En esta categoría, según la norma, se encuentran:
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 2.</b> <i>Pequeños electrodomésticos</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/11.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") El papel de la electrónica es poder prestar un servicio de mantenimiento a los clientes de estos equipos que varias veces producen apego en sus usuarios. El técnico o tecnólogo deberá encontrar las fallas del pequeño electrodoméstico para solucionar y devolverlo al cliente, aplicando los protocolos de servicio del fabricante.
            
        .row(titulo="Equipos de informática y telecomunicaciones")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Los equipos de informática y telecomunicaciones son una variedad especial de los equipos electrónicos con alto uso y alto volumen de equipos, con diferentes fabricantes en América del Norte, Europa, Japón China y Corea del Sur; para su mantenimiento, se requiere recibir capacitación del fabricante o distribuidor autorizado que se encarga de la comercialización y garantías a nivel nacional.  
            p(data-aos="zoom-in") Estas capacitaciones requieren tener las habilidades para comprender el idioma inglés y posteriormente utilizar el protocolo de fallas, aplicando programas de reconocimiento de fallas suministrados por el fabricante, el cual también revisa periodos de garantía normal o garantía extendida y aquellas garantías de por vida para ciertas fallas como soporte del fabricante. En esta categoría, según la norma, se encuentran: 
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 3.</b> <i>Equipos de informática y telecomunicaciones</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/12.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Actualmente, los equipos de informática y telecomunicaciones son utilizados en diferentes campos de actividades, como la industria, el comercio, la educación, el sector agropecuario, la investigación en diferentes áreas, para la comunicación en sí y para la diversión.

        .row(titulo="Aparatos electrónicos de consumo")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Son utilizados para la diversión y el entretenimiento. En sus nuevas tecnologías, están conformados por varias tarjetas de circuitos impresos, las cuales operan y controlan la entrada de energía y la interconexión con otros equipos o con señales de video y audio entregadas, a su vez, por otros aparatos o redes, y la propia salida del mismo sea audio, video u otras. En esta categoría, según la norma, se encuentran: 
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 4.</b> <i>Aparatos electrónicos de consumo</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/13.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Para su mantenimiento, también es importante la capacitación técnica recibida por el fabricante u operador autorizado. Tienen protocolos de revisión de fallas y de mantenimiento preventivo y correctivo. 

        .row(titulo="Aparatos de alumbrado")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Algunos de ellos son de reemplazo directo por falla media o falla total, sin embargo, algunos pueden ser objeto de mantenimiento eléctrico o electrónico.  Realmente, como lo dice la tabla, las bombillas incandescentes no hacen parte de los equipos electrónicos. En esta categoría, según la norma, se encuentran: 
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 5.</b> <i>Aparatos de alumbrado</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/14.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") En todo mantenimiento, como se ha observado, se deben seguir las instrucciones de calidad y fichas técnicas de los fabricantes, para prestar el mejor servicio al usuario final. 

        .row(titulo="Herramientas eléctricas o electrónicas")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Estos tipos de equipos, con el auge de la electrónica, han pasado de ser herramientas básicas con bases electromecánicas a equipos que tienen control de operación, según tarea a realizar, basados en tarjetas de circuitos impresos, con el objeto de facilitar mantenimientos o actividades que se realizan con ellos. En esta categoría, según la norma, se encuentran:
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 6.</b> <i>Herramientas eléctricas o electrónicas</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/15.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Para realizar el mantenimiento de las herramientas, se deben seguir los protocolos de revisión del fabricante, ya sean equipos eléctricos o electrónicos, para dar satisfacción al cliente que busca garantía o mantenimiento preventivo o correctivo.

        .row(titulo="Juguetes o equipos deportivos y de tiempo libre")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Dentro de los equipos electrónicos, se presentan como una clasificación por uso. Tienen control de mantenimiento de acuerdo con su complejidad y por su integración mediante tarjetas de circuito impreso, asumiendo la aplicación de los protocolos de los fabricantes; algunos de ellos se pueden conectar a servicios de soporte en línea y acceso remoto para revisión. En esta categoría, según la norma, se encuentran: 
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 7.</b> <i>Juguetes o equipos deportivos y de tiempo libre </i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/16.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") La electrónica incorporada en juguetes o equipos deportivos hace de la vida más fácil para el ser humano y facilita que el uso de estos equipos electrónicos sea de mayor duración.

        .row(titulo="Aparatos médicos")
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Todos los equipos médicos considerados equipos electrónicos están fundamentados en tarjetas de circuito impreso de alta eficiencia y confiabilidad, esto es alta precisión; por tal razón, los componentes deben cumplir las especificaciones de las fichas técnicas para su fabricación. 
          .col-lg-10.col-12.mb-4
            .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
              p.titulo.pb-0.mb-0 <b>Tabla 8.</b> <i>Aparatos médicos</i>
          .col-lg-10.col-12.mb-4.offset-lg-1(data-aos="zoom-out-right")
            figure
              img(src='@/assets/curso/temas/tema1/17.svg', alt='')
          .col-md-12.mb-4.mb-md-0
            p(data-aos="zoom-in") Los protocolos de mantenimiento preventivo y correctivo de los equipos médicos son rigurosos y se deben cumplir obligatoriamente. Es importante seguir las instrucciones de los manuales en español o inglés. En caso de que los equipos no pasen las pruebas del protocolo de mantenimiento, deberían ser enviados a un taller especializado o al fabricante directamente para su calibración.  

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
