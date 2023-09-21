<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 Ya se conoció en detalle las diferentes temáticas abordadas en este componente formativo, ahora es momento de verlas de manera resumida y puntual a través del siguiente esquema conceptual:

    .row.justify-content-center.mb-5
      .col-lg-8
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="La figura ilustra la síntesis del componente relacionado con los incidentes informáticos que pueden ocurrir, tales como amenazas, riesgos y vulnerabilidades. Se consideran además tipos de amenazas web, planes de mejora y vulnerabilidades, según el Top 10 de OWASP. Para abordar estos incidentes de manera efectiva, se implementan auditorías forenses de forma continua.")
    
    .row.justify-content-center
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
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
