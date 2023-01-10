<script>
import navBar from './components/navBar.vue'
import articleMain from './components/articleMain.vue'
import footerLink from './components/footerLink.vue'

export default {
  name: 'AppDC',
  components: {
    navBar,
    articleMain,
    footerLink
  }
}


</script>

<template>
  <header>
    <navBar/>
  </header>

  <main>
    <articleMain/>
  </main>

  <footer>
    <footerLink/>
  </footer>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;

</style>
