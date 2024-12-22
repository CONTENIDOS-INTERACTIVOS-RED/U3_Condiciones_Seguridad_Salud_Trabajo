<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Resolución 0312 del 2019'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

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
