<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Incidentes informáticos

    .row.justify-content-center.align-items-center.mb-4
      .col-md-8.order-md-1.order-2(data-aos="fade-right")
        p Dentro del tratamiento de incidentes de seguridad digital en las aplicaciones web, parte de la normatividad la establece el Ministerio de Tecnologías de Información y las Comunicaciones de Colombia mediante la Resolución 500 del año 2021 Por la cual se establecen los lineamientos y estándares para la estrategia de seguridad digital y se adopta el modelo de seguridad y privacidad como habilitador de la política de gobierno digital”; por ello se debe recordar que al existir incidentes informáticos el Código Penal establece sanciones legales mediante la #[strong Ley 1273 de 2009].
        p.mb-0 Igualmente, hay que tener en cuenta los marcos de referencia ante un incidente de seguridad de la información guiándose con la #[strong ISO 27035] que es la norma de gestión de incidentes de seguridad de la información, el ciclo de vida de la gestión y contradicción de un incidente informático, así:
      .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/temas/t1/img01.png" alt='')

    .titulo-sexto.color-acento-contenido.my-4(data-aos="fade")
      p.mb-0 #[b Figura 1.] Ciclos incidentes informáticos
    
    .row.justify-content-center.mb-5
      .col-lg-10.BG01.p-5(data-aos="fade-down")
        img(src="@/assets/curso/temas/t1/img02.svg" alt="La figura representa los ciclos de incidentes informáticos. El primer ciclo es la detección y el análisis; el segundo abarca los contenidos, la radicación y la recuperación; el tercero se enfoca en las actividades posteriores al incidente; y el cuarto es la preparación.")
      .col-lg-10.BG02.p-4(data-aos="fade-down")
        p El ciclo siempre será repetitivo, el mismo puede controlarse o auditarse mediante políticas de seguridad de la información y que la organización tenga un departamento en atención frente a los diferentes incidentes de seguridad como un CSIRT como lo indica el Conpes 3701 de 2011; es necesario recordar que dentro los pilares de la información están:
        ul.lista-ul--color.color-terciario.ms-4.fa-ul
          li.mb-1
            i.fas.fa-check
            | Confidencialidad.
          li.mb-1
            i.fas.fa-check
            | Integridad.
          li
            i.fas.fa-check
            | Disponibilidad.  

    p.mb-4(data-aos="fade") Los incidentes informáticos de seguridad en aplicaciones web pueden darse mediante técnicas de ingeniera social o #[i hacking] no autorizados, #[i malware] y SQL #[i injection], como puede verse a continuación:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-7.BG13.p-4
        img(src="@/assets/curso/temas/t1/fig2.png" alt="La figura muestra los tipos de incidentes web que se presentan, los cuales pueden incluir ingeniería social, SQL, inyección, phishing y malware.")

    p.mb-4(data-aos="fade") Se invita a conocer algunos conceptos importantes que identificará en el transcurso de este componente:

    TabsA.color-acento-contenido(data-aos="fade-down") 
      .tarjeta.color-acento-contenido--borde.p-4(titulo="<em>Malware</em>")
        .row.justify-content-center
          .col-md-8.order-md-1.order-2
            h4 #[i Malware]
            p Programas maliciosos que realizan acciones dañinas en un sistema informático.
          .col-md-2.col-4.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t1/img04.png" alt='')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Ingeniería social")
        .row.justify-content-center
          .col-md-8.order-md-1.order-2
            h4 Ingeniería social
            p Técnicas usadas por organizaciones cibercriminales donde utilizan técnicas de engaño para que usuarios con desconocimiento o incautos envíen con facilidad datos confidenciales.
          .col-md-2.col-4.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t1/img05.png" alt='')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="SQL <em>Injection</em>")
        .row.justify-content-center
          .col-md-8.order-md-1.order-2
            h4 SQL #[i Injection]
            p Técnicas donde se usa código fuente realizando infiltraciones.
          .col-md-2.col-4.order-md-2.order-1.mb-md-0.mb-4
            img(src="@/assets/curso/temas/t1/img06.png" alt='')
      
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
