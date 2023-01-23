<script>
import appHeader from './components/appHeader.vue'
import appMain from './components/appMain.vue'
import appFooter from './components/appFooter.vue'


export default {
  name: 'appVue',
  components: {
    appHeader,
    appMain,
    appFooter,
  }
}


</script>

<template>
  <header>
    <appHeader/>
  </header>

  <main>
    <appMain/>
  </main>

  <footer>
    <appFooter/>
  </footer>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
main{
  background-color: $nav-color;
  color: $main-color;
  width: 100%;
}

</style>
