<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Atención al cliente

    p.mb-3(data-aos="zoom-in") La atención al cliente es un aspecto muy importante en una empresa, sea de venta de productos o de servicios. Estas dos actividades tienen injerencia en el sector electrónico, venta de productos manufacturados, como las tarjetas de circuitos impresos, en este caso, o el servicio de mantenimiento, por ejemplo.  
    p.mb-3(data-aos="zoom-in") La atención al cliente inicia con el primer contacto, sea presencial o en línea (sincrónico o asincrónico), en el cual se debe dar la información necesaria a la persona, quien puede ser un futuro cliente o alguien quien regresa. Este mensaje debe ser veraz, rápido y conciso. La atención debe estar pensada para mantenerse y evolucionar de acuerdo con las nuevas tendencias. Por ello, la atención se debe mantener durante todo el proceso de compra/venta del producto o servicio y debe permanecer durante la posventa para atender los siguientes aspectos. 

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10.col-12.mb-4
        .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
          p.titulo.pb-0.mb-0 <b>Figura 7.</b> <i>Atención posventa</i>
      .col-lg-10.col-12.mb-5(data-aos="zoom-out-right")
        figure
          img(src='@/assets/curso/temas/tema2/1.svg', alt='')

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-12
          .row.justify-content-center.align-items-center
            .col-12.px-0(data-aos="fade-left")
              .cajon.color-primario
                .row.justify-content-center.align-items-center.py-0.mt-1
                  .col-12.mt-4.mb-4.px-5
                    p.mb-lg-0.lg-mb-5 El servicio se usa hasta para felicitar al cliente, si es persona natural, el día del cumpleaños o al encargado de las compras, en caso de empresas (personas jurídicas).

    p.mb-3(data-aos="zoom-in") El protocolo de servicio y atención a clientes internos y externos se define en el sistema de gestión de calidad de la empresa, el cual debe ser cumplido por todos los empleados; generalmente, incluye el procedimiento para la atención al cliente interno y externo.  En la siguiente figura, se clarifica quiénes pertenecen a cada categoría.

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10.col-12.mb-4
        .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
          p.titulo.pb-0.mb-0 <b>Figura 8.</b> <i>Tipos de clientes</i>
      .col-lg-10.col-12.mb-5(data-aos="zoom-out-right")
        .cajon.mt-4.py-2.py-lg-4
          LineaTiempoB.color-acento-contenido.mb-5(:datos="datosLineaTiempoB")

    p.mb-3(data-aos="zoom-in") Los protocolos de servicio al cliente no se deben confundir con los protocolos técnicos descritos en las hojas de fichas técnicas o en los manuales técnicos. Los protocolos de servicio al cliente están fundamentados en los estándares de las normas ISO 2000, determinadas por la ISO y aplicadas por diferentes organismos certificadores, como ICONTEC, AENOR, Bureau Veritas, entre otros.
    p.mb-3(data-aos="zoom-in") Se pueden encontrar muchos ejemplos de protocolos de servicios, pero cada empresa construye su propio protocolo en atención al servicio que presta o vende, o al producto como tal; asimismo, al tamaño de la empresa, al volumen de ventas u otras características adicionales particulares, por lo cual, para establecer el protocolo de servicio, se debe trabajar en equipo con las personas del grupo de calidad o un asesor contratista. 

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-12
          .row.justify-content-center.align-items-center
            .col-12.px-0(data-aos="fade-left")
              .cajon.color-primario
                .row.justify-content-center.align-items-center.py-0.mt-1
                  .col-12.mt-4.mb-4.px-5
                    p.mb-lg-0.lg-mb-5 La responsabilidad del sistema de calidad siempre está en la Dirección de la empresa o entidad .

    p.mb-3(data-aos="zoom-in") El estatuto del consumidor es la norma de un país para controlar los servicios que se ofrecen a los consumidores, prevaleciendo los derechos de estos. En Colombia, se creó el estatuto del consumidor mediante la Ley 1480 de 2011, sin embargo, anteriormente existían algunas normatividades sobre el tema, las cuales fueron compiladas en el estatuto para una mejor aplicación y uso por parte de los consumidores. 
    p.mb-3(data-aos="zoom-in") Dentro de los principios generales, de acuerdo con Accounter (2015), esta Ley, que beneficia a todos los colombianos, decreta lo siguiente.

    //- .row.justify-content-center.align-items-center.mt-5
    //-   .col-lg-10.col-12.mb-4
    //-     .titulo-sexto.color-acento-contenido.mb-0.offset-lg-3(data-aos="fade-left")
    //-       p.titulo.pb-0.mb-0 <b>Figura 9.</b> <i>Principios generales</i>
    //-   .col-lg-12.col-12.mb-5(data-aos="zoom-out-right")
    //-     figure
    //-       img(src='@/assets/curso/temas/tema2/6.png', alt='')

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-6.col-lg-2.mb-4.mb-lg-0
        .tarjeta--boton.color-gris.p-4(style="height:100%")
          .row.justify-content-center.align-items-center(style="height:100%")
            .col-auto
              figure
                img(src='@/assets/curso/temas/tema2/6.png', alt='Texto que describa la imagen')
            .col
              p.text-small.mt-3 La protección de los consumidores frente a los riesgos para su salud y seguridad.
              br
              br
              br
            
      .col-sm-6.col-lg-2.mb-4.mb-lg-0
        .tarjeta--boton.color-gris.p-4(style="height:100%")
          .row.justify-content-center.align-items-center(style="height:100%")
              .col-auto
                figure
                  img(src='@/assets/curso/temas/tema2/8.svg', alt='Texto que describa la imagen')
              .col-auto
                p.text-small.mt-3 El acceso de los consumidores a una información adecuada, de acuerdo con los términos de esta Ley, que les permita hacer elecciones bien fundamentadas.
      
      .col-sm-6.col-lg-2.mb-4.mb-lg-0
        .tarjeta--boton.color-gris.p-4 
          .row.justify-content-center.align-items-center
            .col-auto
              figure
                img(src='@/assets/curso/temas/tema2/9.svg', alt='Texto que describa la imagen')
            .col-auto
              p.text-small.mt-3 El acceso de los consumidores a una información adecuada, de acuerdo con los términos de esta Ley, que les permita hacer elecciones bien fundamentadas.

      .col-sm-6.col-lg-2.mb-4.mb-lg-0
        .tarjeta--boton.color-gris.p-4
          .row.justify-content-center.align-items-center
            .col-auto
              figure
                img(src='@/assets/curso/temas/tema2/10.svg', alt='Texto que describa la imagen')
            .col-auto 
              p.text-small.mt-3 El acceso de los consumidores a una información adecuada, de acuerdo con los términos de esta Ley, que les permita hacer elecciones bien fundamentadas.

      .col-sm-6.col-lg-2.mb-4.mb-lg-0
        .tarjeta--boton.color-gris.p-4
          .row.justify-content-center.align-items-center
            .col-auto
              figure
                img(src='@/assets/curso/temas/tema2/11.svg', alt='Texto que describa la imagen')
            .col-auto
              p.text-small.mt-3 El acceso de los consumidores a una información adecuada, de acuerdo con los términos de esta Ley, que les permita hacer elecciones bien fundamentadas.
    
    .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="zoom-out-up")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            p Una fórmula infalible para determinar la calidad de un producto es su relación con el costo. Es indudable que la calidad cuesta. Es probable que  una pieza musical en un equipo barato suene con determinada calidad y luego esa misma pieza en un equipo costoso no se note mayor diferencia en el sonido, pero las diferencias comienzan a notarse con el paso del tiempo al tratar de percibir esa misma sensación, es probable que el equipo barato ya presente algún desgaste y solo hasta entonces se pueda percibir alguna diferencia notable en la calidad del sonido.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema2/12.svg', alt='')

        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            p Lo mismo puede pasar con un televisor, ya que es probable que dos equipos con características de fabricación diferentes, uno barato y otro costoso, en un principio no se note mucha diferencia en cuanto a la imagen. Sin embargo, a medida que pasa el tiempo, empiezan a notarse la disparidad.
          .col-md-5
            figure
              img(src='@/assets/curso/temas/tema2/13.svg', alt='')

              
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-12
          .row.justify-content-center.align-items-center
            .col-12.px-0(data-aos="fade-left")
              .cajon.color-primario
                .row.justify-content-center.align-items-center.py-0.mt-1
                  .col-12.mt-4.mb-4.px-5
                    p.mb-lg-0.lg-mb-5 La Superintendencia de Industria y Comercio es la entidad que atiende las quejas de los consumidores respecto de las empresas o establecimientos, por fallas en el servicio, mala calidad, entrega diferente de producto respecto del ofrecido, entre muchas otras, como engaños, fraudes, etc .
    
    p.mb-3(data-aos="zoom-in") Ahora bien, los términos de garantía legal hacen parte del contrato y/o factura de compra del producto o del servicio a ser prestado por la empresa. Con la firma del contrato o factura, se aceptan los términos de garantías legales. 
    p.mb-3(data-aos="zoom-in") La garantía está encaminada a proteger al consumidor (comprador) frente al fabricante y/o comercializador por daños que pueda ocasionar el producto o servicio a los equipos, instalaciones o personas del cliente. 

    .col.lg-12.col-lg-10.offset-lg-1 
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/7.jpg')})`}"
        )
        .bloque-texto-g__texto.p-4.mt-5
          p.mb-0(data-aos="fade-up") Por un mal servicio o por un producto defectuoso, la garantía le permite al cliente solicitar que el fabricante o comercializador repare o resarza los daños o imprevistos que los defectos del producto o servicio generan en los planes del cliente (comprador).
          br
          br
          br
          br
    
    p.mt-3(data-aos="zoom-in") Finalmente, la normativa legal, por su parte, permite a los consumidores crear asociaciones u organizaciones de estos, en aras de proteger los derechos del consumidor.  La normativa busca promover el derecho del consumidor y está basada en los principios de la jurisprudencia y la academia, quienes buscan llenar la reglamentación del estatuto del consumidor.  
    p.mb-3(data-aos="zoom-in") La normativa actual para Colombia está fundamentada en la Ley 1480 de 2011, reglamentación establecida para la protección del consumidor, en concordancia con los Códigos de Comercio y Civil, en protección de los usuarios, especialmente en las garantías, opción de retracto, defensa contra cláusulas abusivas, condiciones generales de contratación, etc. 

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-12
          .row.justify-content-center.align-items-center
            .col-12.px-0(data-aos="fade-left")
              .cajon.color-primario
                .row.justify-content-center.align-items-center.py-0.mt-1
                  .col-12.mt-4.mb-4.px-5
                    p.mb-lg-0.lg-mb-5 La tarea normativa es de carácter interpretativa e integradora, tiene el principio de encuadrar la protección efectiva de la autónoma e independiente potestad del consumidor de disponer de sus derechos, pero también la responsabilidad de cumplir con estas facultades .



</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    datosLineaTiempoB: [
      {
        titulo: '',
        texto:
          'Los clientes son los mismos empleados o, en algunos casos, como en las instituciones educativas, son sus estudiantes. ',
        icono: require('@/assets/curso/temas/tema2/2.svg'),
      },
      {
        titulo: '',
        texto:
          'Los clientes externos son quienes reciben un producto o servicio de la empresa, compradores o quienes utilizan los servicios de la misma.',
        icono: require('@/assets/curso/temas/tema2/3.svg'),
      },
      {
        titulo: '',
        texto:
          'Existen otros roles que por lo general se involucran, como los proveedores y los terceros, quienes se caracterizan por prestar un servicio interno, como la seguridad o vigilancia contratada, tecnología, servicios de aseo y/o cafetería. Cuando estos servicios son contratados con un tercero (outsourcing), ellos deben cumplir el protocolo interno.',
        icono: require('@/assets/curso/temas/tema2/4.svg'),
      },
    ],
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
