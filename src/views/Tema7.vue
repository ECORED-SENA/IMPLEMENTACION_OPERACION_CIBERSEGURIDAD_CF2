<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 7
      h1 Valoración

    .row
      .col-lg-7.mb-4(data-aos="fade-right")
        p La valoración de riesgos es un proceso que inicia con la valuación de los activos de información, luego pasa por la valoración de la probabilidad de ocurrencia de riesgos asociados a los activos y termina con la valoración del impacto.
        p.fondo-naranja.mb-0.p-4 En términos generales el riesgo es igual a la probabilidad por impacto; 
          span.etiqueta Riesgo = Probabilidad x Impacto. 
          | Pero en ciberseguridad el impacto está determinado por el valor del activo de información por el impacto general de las dimensiones de impacto organizacionales. 
      .col-lg-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema7-imagen.jpg', alt='imagen decorativa')   

    Separador


    // 7.1
    #t_7_1.titulo-segundo(data-aos="fade-right")
      .h2 7.1  Riesgo inherente

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10.fondo-rosado
        .row.align-items-center.justify-content-center.py-md-4.p-4
          .col-md-3.mb-md-0.mb-3
            img(src='@/assets/curso/tema7-1-imagen.svg', alt='imagen decorativa') 
          .col-md-8
            p Consiste en el riesgo valorado antes de que se le haya aplicado un tratamiento o controles para su mitigación. También es denominado riesgo potencial.

    p.mb-4(data-aos="fade") Sobre el riesgo inherente, se debe tener en cuenta:





</template>

<script>
export default {
  name: 'Tema7',
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

<style lang="sass" scoped></style>
