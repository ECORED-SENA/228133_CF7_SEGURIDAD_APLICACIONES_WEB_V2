<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-4(data-aos="fade") Le damos la bienvenida al componente formativo denominado 
      span.fw-bold.BG02 “Incidentes y vulnerabilidades en seguridad orientada a aplicaciones web”
      | , el cual hace parte del programa de formación técnico en Seguridad en aplicaciones web, para lo cual se invita a observar el siguiente video:

    figure(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/nmWZ75V7KHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Incidentes y vulnerabilidades en seguridad orientada a aplicaciones web


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
