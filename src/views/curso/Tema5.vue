<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'5. ISO 45001 del 2018'")
  .container.tarjeta.tarjeta--blanca.px-4.px-md-5


</template>

<script>
export default {
  name: 'Tema4',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.material-complementario
  padding-top: 3rem
  border-top: 9px solid $color-sistema-e
</style>
