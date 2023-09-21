<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Recolección de evidencia digital

    p.mb-4(data-aos="fade") La IOCE (Organización Internacional de Evidencia Computacional) estableció en el año 1999 cinco principios internacionales para tener en cuenta para el adecuado manejo de la evidencia digital. #[strong Se invita a saber de qué tratan]:

    SlyderF.mb-5(columnas="col-lg-4 col-md-6" data-aos="fade-down")
      .BG06.pt-5.mx-2
        .row.justify-content-center.BG05.B-R5
          .col-lg-7.col-md-7.col-6
            img.img01(src="@/assets/curso/temas/t3/img01.png" alt='')
        .row.justify-content-center.BG02.p-4.pb-4.B-R5
          .col-auto.img02.BGR06.p-2
            h4.mb-0.text-center.px-4 Principio 1
          p.mb-0 Al recolectar la evidencia digital se deben tomar acciones para asegurarse de que no se modificará dicha evidencia.
      .BG06.pt-5.mx-2
        .row.justify-content-center.BG07.B-R5
          .col-lg-7.col-md-7.col-6
            img.img01(src="@/assets/curso/temas/t3/img02.png" alt='')
        .row.justify-content-center.BG08.p-4.pb-4.B-R5
          .col-auto.img02.BGR06.p-2
            h4.mb-0.text-center.px-4 Principio 2
          p.mb-0 Cuando una persona necesite acceder a la evidencia digital original, se debe asegurar que sea un investigador forense competente.
      .BG06.pt-5.mx-2
        .row.justify-content-center.BG05.B-R5
          .col-lg-7.col-md-7.col-6
            img.img01(src="@/assets/curso/temas/t3/img03.png" alt='')
        .row.justify-content-center.BG02.p-4.pb-4.B-R5
          .col-auto.img02.BGR06.p-2
            h4.mb-0.text-center.px-4 Principio 3
          p.mb-0 Toda la actividad relacionada con la recolección, acceso, almacenamiento o transferencia de evidencia digital debe estar documentada, preservada y disponible para ser revisada.
      .BG06.pt-5.mx-2
        .row.justify-content-center.BG07.B-R5
          .col-lg-7.col-md-7.col-6
            img.img01(src="@/assets/curso/temas/t3/img04.png" alt='')
        .row.justify-content-center.BG08.p-4.pb-4.B-R5
          .col-auto.img02.BGR06.p-2
            h4.mb-0.text-center.px-4 Principio 4
          p.mb-0 Un individuo es responsable por todas las acciones realizadas sobre la evidencia digital mientras esta se encuentre en su posesión.
      .BG06.pt-5.mx-2
        .row.justify-content-center.BG05.B-R5
          .col-lg-7.col-md-7.col-6
            img.img01(src="@/assets/curso/temas/t3/img05.png" alt='')
        .row.justify-content-center.BG02.p-4.pb-4.B-R5
          .col-auto.img02.BGR06.p-2
            h4.mb-0.text-center.px-4 Principio 5
          p.mb-0 Cualquier agencia que sea responsable de la recolección, acceso, almacenamiento o transferencia de evidencia digital es responsable de cumplir con los principios anteriores.

    
    .row.fondo-tema3.align-items-center.pt-5.mb-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center
    
          p.mb-4(data-aos="fade") Además, toda evidencia digital es frágil y volátil, por lo que la misma se debe recolectar de manera adecuada para no ponerla en duda. A continuación, se relaciona el ciclo de la evidencia digital:

          .col-lg-6.col-md-10.mb-5(data-aos="fade-down")
            img(src="@/assets/curso/temas/t3/img06.svg" alt="La figura ilustra la síntesis del componente relacionado con los incidentes informáticos que pueden ocurrir, tales como amenazas, riesgos y vulnerabilidades. Se consideran además tipos de amenazas web, planes de mejora y vulnerabilidades, según el Top 10 de OWASP. Para abordar estos incidentes de manera efectiva, se implementan auditorías forenses de forma continua")

          .cajon.color-acento-botones.p-4(data-aos="fade-down")
            p.mb-0 Cuando se habla de adquisición en el análisis forense, se hace con base en los parámetros del formato cadena de custodia quien halla, recolecta y embala la misma; la preservación nos indica la técnica con la herramienta de #[i software] forense utilizada para mantener la idoneidad de esta.

    
    .row.justify-content-center.align-items-center
      .col-md-4.mb-3.mb-lg-0(data-aos="fade-right")
        img(src="@/assets/curso/temas/t3/img07.png" alt='')
      .col-md-8(data-aos="fade-left")
        p El análisis es aquel que se realiza en el laboratorio forense para realizar procedimientos en caso de borrado de navegación o al sistema de información, en la documentación debe ir explicado todo desde el inicio: características informáticas del #[i software], método utilizado, identificación del perito informático, tamaño de la información, nombre y versiones del #[i software] forense usado. La presentación es la terminación de ese informe junto con la evidencia digital recolectada cumpliendo los procedimientos forenses, y las conclusiones son con base en lo analizado y lo que no se pudo recuperar.

      

</template>

<script>
export default {
  name: 'Tema3',
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
