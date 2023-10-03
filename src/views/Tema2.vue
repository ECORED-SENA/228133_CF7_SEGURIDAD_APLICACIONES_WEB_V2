<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Auditoría forense

    .row.justify-content-center.align-items-center.mb-4
      .col-md-8.order-md-1.order-2(data-aos="fade-right")
        p Las auditorías forenses se realizan cuando los incidentes informáticos pasan a ser denunciados penal o administrativamente y se requieren para las investigaciones legales pertinentes, también se pueden realizar auditorías forenses para detener los incidentes informáticos y fortalecimiento de acciones dentro de la organización. En Colombia la ley con que más se enfrentan los ataques cibernéticos es la Ley 1273 de 2009 por la que se crea el bien jurídico tutelado y el dato. 
        p Se recomienda que las auditorías forenses sean realizadas por externos y que tengan conocimiento en procedimientos de informática forense y derecho informático, esto debido que al recaudar evidencias digitales en un futuro las sustentará ante un estrado judicial.
      .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/temas/t2/img01.png" alt="")
    
    .row.justify-content-center.BG02.p-4(data-aos="fade-down")
      h5.text-center.mb-4 Las etapas de la auditoría forense se conforman de la siguiente manera:
      .col-12.tarjeta.tarjeta--blanca.p-4
        .row.justify-content-around
          .col-lg.col-md-5.col-8.mb-lg-0.py-4.py-lg-0.B-3
            .row.justify-content-center.mb-4
              .col-lg-5.col-md-3.col-5
                img(src="@/assets/curso/temas/t2/img02.png" alt="")
            h5.text-center.mb-0 Realización de auditoría forense.
          .col-lg.col-md-5.col-8.mb-lg-0.py-4.py-lg-0.B-3
            .row.justify-content-center.mb-4
              .col-lg-5.col-md-3.col-5
                img(src="@/assets/curso/temas/t2/img03.png" alt="")
            h5.text-center.mb-0 Definición de programas de auditoría forense.
          .col-lg.col-md-5.col-8.mb-lg-0.py-4.py-lg-0.B-3
            .row.justify-content-center.mb-4
              .col-lg-5.col-md-3.col-5
                img(src="@/assets/curso/temas/t2/img04.png" alt="")
            h5.text-center.mb-0 Ejecución de la auditoría forense.
          .col-lg.col-md-5.col-8.mb-lg-0.py-4.py-lg-0.B-3
            .row.justify-content-center.mb-4
              .col-lg-5.col-md-3.col-5
                img(src="@/assets/curso/temas/t2/img05.png" alt="")
            h5.text-center.mb-0 Elaboración del informe de auditoría forense.
          .col-lg.col-md-5.col-8.py-4.py-lg-0
            .row.justify-content-center.mb-4
              .col-lg-5.col-md-3.col-5
                img(src="@/assets/curso/temas/t2/img06.png" alt="")
            h5.text-center.mb-0 Entrega del informe al cliente.
          

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 2.1	Informática forense 
    
    .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t2/img07.jpg')})`}")
      .bloque-texto-g__texto.p-5(data-aos="fade-left")
        p.mb-0 La informática forense es considerada la ciencia del futuro, la misma se realiza mediante la recopilación de #[i log] de auditoría del sistema o aplicación, o recuperar información borrada en los incidentes informáticos. En este proceso de incidentes se debe documentar y grabar los procedimientos e indicar los #[i software] forenses utilizados y procedimientos según los protocolos nacionales e internacionales.

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
        .cajon-b.color-acento-botones.p-3
          p.mb-0 El cómputo forense ayuda a detectar y analizar todas las pistas sobre ataques informáticos, conversaciones, robos de información o evidencia digital al navegar por internet, accesos no autorizados a aplicaciones y correos electrónicos. La finalidad es la de identificar, preservar, extraer y documentar para que estas evidencias digitales pasen a ser pruebas en un estrado judicial.
      .col-lg-4.col-8.order-lg-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/temas/t2/img08.png" alt="")
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-7(data-aos="fade-right")
        img.px-lg-4(src="@/assets/curso/temas/t2/img09.png" alt="")
      .col-lg-6(data-aos="fade-left")
        .cajon-b.color-acento-botones.p-3
          p.mb-0 En Colombia, existe la unidad de delitos informáticos de la Fiscalía General de la Nación y el CAI virtual de la DIJIN unidad de incidentes informáticos. Cuando una aplicación #[i web] es vulnerada se debe identificar por medio de la Informática forense de dónde provino el ataque, cuál fue la técnica utilizada y revisar las posibles vulnerabilidades de la herramienta para tomar los correctivos de esta.
    
    
    Separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 2.2	Tableros de control
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-3.mb-lg-0(data-aos="fade-right")
        img(src="@/assets/curso/temas/t2/img16.svg" alt="")
      .col-lg-8(data-aos="fade-left")
        p Los tableros de control se utilizan en las auditorías forenses para realizar chequeos y sacar conclusiones rápidamente, estos sirven para realizar tomas de información mediante los tableros de control; uno de ellos podría ser el siguiente: 
        .row.justify-content-around.align-items-center.tarjeta.color-secundario.p-4
          .col-3.col-sm-2.col-lg-1.px-lg-1
            img(src="@/assets/curso/temas/pdf.svg" alt="")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h4.text-white Tablero de control análisis intermedio Auditoría forense
                p.text-white.mb-0 Se invita a consultar el siguiente documento anexo para ampliar sus conocimientos
              .col-sm-auto
                a.boton.color-acento-botones(:href="obtenerLink('downloads/Tablero_control_analisis_intermedio_Auditoria_forense.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download
      
    p.mb-4(data-aos="fade") En los dominios se puede colocar el tipo del ciclo del PHVA, el tipo de proceso sería el de evaluar y administración de riesgos informáticos y dentro de cada objetivo de control son los contextos, identificación, evolución, evaluación o respuestas de los riesgos. 

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-7.col-md-9.BG02.p-4.order-md-1.order-2
        .h4 Como auditores, en cada ítem se realizan preguntas y se ejecuta como:
        .row.justify-content-center.align-items-center.mb-4
          .col-2
            img.w-75(src="@/assets/curso/temas/t2/img12.svg" alt="")
          .col-8
            p.mb-0 #[strong Planear] = ¿Qué hacer? ¿Cómo hacerlo?
        .row.justify-content-center.align-items-center.mb-4
          .col-2
            img.w-75(src="@/assets/curso/temas/t2/img13.svg" alt="")
          .col-8
            p.mb-0 #[strong Hacer] = Ejecutar lo proyectado.
        .row.justify-content-center.align-items-center.mb-4
          .col-2
            img.w-75(src="@/assets/curso/temas/t2/img14.svg" alt="")
          .col-8
            p.mb-0 #[strong Verificar] = ¿Las cosas transitaron según cronograma planteado?
        .row.justify-content-center.align-items-center.mb-4
          .col-2
            img.w-75(src="@/assets/curso/temas/t2/img15.svg" alt="")
          .col-8
            p.mb-0 #[strong Actuar] = ¿Cómo mejorar la próxima vez?
      .col-lg-3.col-md-3.col-6.BG03.p-4.order-md-2.order-1.mb-md-0.mb-4.d-flex.align-items-center
        img(src="@/assets/curso/temas/t2/img10.png" alt="")
    
    p.mb-4(data-aos="fade") 
      span.BG23.fw-bold.p-1 Al empezar a aplicar el ciclo PHVA,
      |  en la acción planear se debe conocer los procesos digitales críticos en la organización, luego detalladamente se analizan, para implementar controles que protejan los procesos implementados ante amenazas cibernéticas.

    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-lg-5.col-7.BG01.p-4.d-flex.align-items-center(data-aos="fade-right")
            p.mb-0 Un ejemplo de un objetivo de control sería: #[b identificación de riesgos].
          .col-lg-3.col-md-4.col-5.BG04.p-5.p-lg-4(data-aos="fade-left")
            img(src="@/assets/curso/temas/t2/img11.png" alt="")
        p Dentro de la lista de chequeo se pueden realizar preguntas y reformular las mismas conforme a la organización, frente al manejo y operación de las aplicaciones #[i web] donde se marca solo un ítem entre sí o no y una observación general en caso de justificar, la misma del ítem seleccionado; de igual forma, se pueden agregar más aspectos a evaluar dependido el análisis o tipo de auditoría o control que requiere realizar el profesional. A continuación se presenta dicho formato:
        .row.justify-content-around.align-items-center.tarjeta.color-secundario.p-4
          .col-3.col-sm-2.col-lg-1.px-lg-1
            img(src="@/assets/curso/temas/pdf.svg" alt="")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h4.text-white Lista de chequeo control básico
                p.text-white.mb-0 Se invita a consultar el siguiente documento anexo para ampliar sus conocimientos
              .col-sm-auto
                a.boton.color-acento-botones(:href="obtenerLink('downloads/Lista_chequeo_control_basico.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download
      .col-lg-4.col-5.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/temas/t2/img17.svg" alt="")
    
    
    
    

        


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
