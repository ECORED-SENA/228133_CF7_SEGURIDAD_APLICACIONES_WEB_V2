<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Informes incidentes de seguridad en aplicaciones

    p.mb-4(data-aos="fade") Antes de iniciar este tema, es importante observar el siguiente video explicativo:

    figure.mb-4(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/F91iy9EWL34" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Informes preliminares


    .row.justify-content-star.align-items-center.mb-4
      .col-lg-7(data-aos="fade-right")
        .cajon-b.color-acento-botones.p-3
          p Los informes se deben presentar claros, concisos y ordenados, los mismos deben ser exhaustivos respecto de las técnicas forenses utilizadas con conclusiones lógicas, bien argumentadas y en un lenguaje técnico, legal y explicativo para los demás.
          p.mb-0 #[b Lo anterior mediante el ASVS], que es un marco de referencia de requisitos de seguridad, controles funcionales y los no funcionales que se requieren al diseñar, desplegar y testear aplicaciones web. Así como con el OWASP top 10 que es el documento principal para tener en cuenta sobre los riesgos de seguridad más destacados en aplicaciones web, como se indica en la tabla a continuación:
      .col-lg-5.col-11.mb-md-0.mb-4.d-lg-block.d-none(data-aos="fade-left")
        img(src="@/assets/curso/temas/t4/img01.png" alt='')

    .titulo-sexto.color-acento-contenido(data-aos="fade-down")
      p.mb-0 #[b Tabla 1.] Metodología de clasificación de riesgo
    .tabla-a.tabla-1.color-acento-botones.mb-5(data-aos="fade-down")
      table
        thead
          tr.BG02.text-center
            th Agente de amenaza
            th Explotabilidad
            th Prevalencia de vulnerabilidad
            th Detección de vulnerabilidad
            th Impacto técnico
            th Impacto de negocio
        tbody
          tr
            th.B-B1(td rowspan="3") Específico de la aplicación.
            td.BG17 3 Fácil.
            td.BG17 3 Difundido.
            td.BG17 3 Fácil.
            td.BG17 3 Severo.
            th.B-B1(td rowspan="3") Específico del negocio.
          tr.BGR09
            td 2 Promedio.
            td 2 Común.
            td 2 Promedio.
            td 2 Moderado.
          tr.BG05.B-B1
            td 1 Difícil.
            td 1 Poco común.
            td 1 Difícil.
            td 1 Mínimo.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-8.tarjeta.color-secundario.p-4.p-lg-3
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1.px-lg-1
            img(src="@/assets/curso/temas/pdf.svg" alt="")
          .col-lg-10.col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h4.text-white Factores de riesgo
                p.text-white.mb-0 Para conocer los factores de riesgo que se asocian a la anterior tabla, le invitamos a descargar el siguiente recurso.
              .col-sm-auto
                a.boton.color-acento-botones(:href="obtenerLink('downloads/Factores_riesgo.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download
                
    p.mb-4(data-aos="fade") Según las tablas anteriores y los niveles de riesgos detectados por cada ítem de análisis en el informe, se debe especificar el tipo de amenaza según la aplicación, así:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-7
        .titulo-sexto.color-acento-contenido.mb-2
          p.mb-0 #[b Tabla 2.] Impacto vs. valoración
        .tabla-a.tabla-2(data-aos="fade-down")
          table
            thead.text-center
              tr.BG07
                th.B-B2 Impacto
                th.B-B2 Descripción
                th.B-B2 Valoración
            tbody.text-center
              tr
                td.B-B2.BG18.text-white Catastrófico
                td.B-B2.BG03 Extremadamente dañino
                td.B-B2.BG18(td rowspan="2").text-white Alto
              tr
                td.B-B2.BG19 Mayor
                td.B-B2.BG03 Dañino
              tr
                td.B-B2.BG20 Moderado
                td.B-B2.BG03 Moderado
                td.B-B2.BG20 Medio
              tr
                td.B-B2.BG21 Menor
                td.B-B2.BG03 Menor
                td.B-B2.BG22(td rowspan="2") Baja
              tr
                td.B-B2.BG22 Insignificante
                td.B-B2.BG03 Ligeramente dañino

    p.mb-4(data-aos="fade") La descripción de la anterior tabla, se puede interpretar de la siguiente manera:

    .tarjeta.BGR01.p-4.mb-5(data-aos="fade-down")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-md-6.order-md-1.order-2
            .h4 Impacto catastrófico y riesgo alto
            p La descripción es #[strong extremadamente dañina], en la misma en el informe se pone el valor de pérdidas superiores a 1.500 SMLV, la afectación de la imagen corporativa a nivel local, regional, nacional e internacional. 
            p Si llega a tener sanciones por entes de control como Fiscalía, Procuraduría y Contraloría, y también analizar si hay graves daños en la infraestructura y aplicaciones web de la organización.
          .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t4/img02.svg" alt='')
        .row.justify-content-center
          .col-md-6.order-md-1.order-2
            .h4 Impacto mayor y riesgo alto
            p Sería una descripción de #[strong tipo dañino] si existen pérdidas económicas entre 1.000 y 1.499 SMLV, si la afectación de la imagen corporativa es a nivel local, regional y nacional. Si llega a tener sanciones por entes de control como Fiscalía, Procuraduría y Contraloría y también analizar si hay graves daños en la infraestructura y aplicaciones web de la organización.
          .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t4/img03.svg" alt='')
        .row.justify-content-center
          .col-md-6.order-md-1.order-2
            .h4 Impacto moderado y riesgo medio
            p Sería una descripción de #[strong tipo moderado] si existen pérdidas económicas entre 600 y 999 SMLV, si la afectación de la imagen corporativa es a nivel local. Si llega a tener sanciones a nivel de la oficina de control interno o jurídico de la entidad, y también analizar si hay daños parciales en la infraestructura y aplicaciones web de la organización.
          .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t4/img04.svg" alt='')
        .row.justify-content-center
          .col-md-6.order-md-1.order-2
            .h4 Impacto es menor y el riesgo bajo
            p Sería una descripción de #[strong tipo menor] si existen pérdidas económicas entre 400 y 599 SMLV, si la afectación de la imagen corporativa es a nivel organizacional. Si llega a tener sanciones a nivel procesos, y también analizar si hay daños pequeños en la infraestructura y aplicaciones web de la organización.
          .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t4/img05.svg" alt='')
        .row.justify-content-center
          .col-md-6.order-md-1.order-2
            .h4 Impacto es insignificante y el riesgo bajo
            p Sería una descripción de tipo #[strong ligeramente dañino] si existen pérdidas económicas menores a 399 SMLV, si la afectación de la imagen corporativa es a nivel de área, si llega a tener sanciones a nivel área, y también analizar si hay daños pequeños en la infraestructura y aplicaciones web de la organización. Hay que revisar si se tiene llamados de atención a nivel grupo.
          .col-md-5.col-8.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t4/img06.svg" alt='')
    
    p(data-aos="fade") En la organización, y en este caso con las aplicaciones web, pueden ocurrir varios impactos y diferentes valoraciones que deben ser documentados y analizados en el informe, y de igual manera establecer un plan de mejora y control frente a incidentes informáticos. 
    p.mb-4(data-aos="fade") En cuanto a la urgencia frente a incidentes informáticos en aplicaciones web, se tienen de la siguiente manera:
    
    .row.justify-content-center.mb-5
      .col-lg-10.BGR09.p-4
        h4.text-center.mb-4 ATENCIÓN A LA URGENCIA
        .row.justify-content-center
          .col-md-4.col-10.mb-md-0.mb-4(data-aos="fade-right")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t4/img07.svg' alt='')
              .tarjeta.BGR10.p-4.pt-5
                p.mt-5.mb-0 El incidente de seguridad debe atenderse entre 0 y 120 minutos.
          .col-md-4.col-10.mb-md-0.mb-4(data-aos="fade")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t4/img08.svg' alt='')
              .tarjeta.BGR11.p-4.pt-5
                p.mt-5.mb-0 El incidente de seguridad debe atenderse entre 0 y 240 minutos.
          .col-md-4.col-10(data-aos="fade-left")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t4/img09.svg' alt='')
              .tarjeta.BGR12.p-4.pt-5
                p.mt-5.mb-0 El incidente de seguridad debe atenderse entre 0 y 1.440 minutos.

    p.mb-4(data-aos="fade") Estos tiempos de respuestas también deben de ser tenidos en cuenta en la realización del informe, tener en cuenta los tiempos mínimos y máximo según el incidente informático en la aplicación web. Es importante establecer políticas de control en las aplicaciones web; la ISO 27001 juega un papel fundamental en ese plan de mejora.

    .row.fondo-green.align-items-center.py-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center
          
          .col-lg-9.order-1(data-aos="fade")
            h4.mb-4 Un informe de auditoría debe contar con todas las evidencias recolectadas (#[i logs], errores humanos detectados, irregularidades) y el procedimiento es el siguiente:
          .col-lg-6.order-md-2.order-3(data-aos="fade-right")
            ul.lista-ul--color.color-verde.ms-4.fa-ul
              li
                i.fas.fa-check
                | Aplicar instrumentos de toma de información.
              li
                i.fas.fa-check
                | Registrar las situaciones encontradas.
              li
                i.fas.fa-check
                | Comentar las situaciones encontradas y sus posibles causas.
              li
                i.fas.fa-check
                | Analizar y depurar las situaciones relevantes.
              li
                i.fas.fa-check
                | Comentar las situaciones relevantes con gerente o directivos.
              li
                i.fas.fa-check
                | Elaborar informe final con dictamen del auditor y plan de mejora.
              li
                i.fas.fa-check
                | Sustentar informe final ante directivos o gerente.
          .col-lg-3.col-5.order-md-3.order-2.mb-md-0.mb-4(data-aos="fade-left")
            img(src='@/assets/curso/temas/t4/img10.png' alt='')
      
  
    p.mb-4(data-aos="fade") En los 
      span.BG23.p-1 #[b informes de incidentes de seguridad en aplicaciones,]
      |  se incluyen los ajustes de controles que hacen referencia a los planes de mejora; así se detienen y previenen futuros incidentes informáticos, ya que los mismos buscan establecer mecanismos de prevención y control. Como política general de ajuste de control se debe contemplar las actualizaciones de #[i software] o parches de seguridad en la herramienta de aplicaciones web cada vez que se detecte una. A continuación, se conocerá los niveles de planes de mejora y tablero de control, básico, intermedio y avanzado:
  
    .row.justify-content-center.mb-4
      .col-lg-3.col-md-6.col-8.mb-3(data-aos="fade-right")
        .BG03.h-100
          .BG14.p-4
            h4.text-white.text-center.mb-0 Básico
          .BG03.p-4.mb-md-0.mb-4
            ul.lista-ul--color.color-verde.fa-ul
              li
                i.fas.fa-check
                | Antivirus.
              li
                i.fas.fa-check
                | Contraseñas fuertes.
              li
                i.fas.fa-check
                span.mb-0 Realizar #[em backup] frecuentes.
              li
                i.fas.fa-check
                | Actualizar app.
      .col-lg-3.col-md-6.col-8.mb-3(data-aos="zoom-in")
        .BG03.h-100
          .BG15.p-4
            h4.text-white.text-center.mb-0 Intermedio
          .BG03.p-4.mb-md-0.mb-4
            ul.lista-ul--color.color-verde.mb-0.fa-ul
              li
                i.fas.fa-check
                | No reciclar contraseñas.
              li
                i.fas.fa-check
                | Usar gestor de contraseñas.
              li
                i.fas.fa-check
                | Actualizar personal.
              li
                i.fas.fa-check
                span.mb-0 Utilizar #[em firewall].
              li
                i.fas.fa-check
                span.mb-0 Proteger servidores web.
      .col-lg-3.col-md-6.col-8.mb-3(data-aos="fade-left")
        .BG03.h-100
          .BG16.p-4
            h4.text-white.text-center.mb-0 Avanzado
          .BG03.p-4
            ul.lista-ul--color.color-verde.fa-ul
              li
                i.fas.fa-check
                | Utilizar cifrado. 
              li
                i.fas.fa-check
                | Actualizar tableros de control de amenazas y riesgos.
              li
                i.fas.fa-check
                span.mb-0 Tener configuraciones avanzadas de seguridad web.

    p.mb-4(data-aos="fade") Los planes de mejora son las conclusiones que toda auditoría deja por defecto tomando correctivos para que los riesgos y amenazas no vuelvan a la aplicación web, con este tipo de control y seguimiento se previenen riesgos y amenazas.
    

</template>

<script>
export default {
  name: 'Tema4',
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
