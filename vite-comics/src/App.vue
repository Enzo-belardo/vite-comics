<script>
import navBar from './components/navBar.vue'
import articleMain from './components/articleMain.vue'
import footerLink from './components/footerLink.vue'
import productMain from './components/productMain.vue';
import JumboComponent from './components/JumboComponent.vue';

export default {
  name: 'AppDC',
  components: {
    navBar,
    articleMain,
    productMain,
    footerLink,
    JumboComponent,

  }
}


</script>

<template>
  <header>
    <navBar/>
  </header>

  <main>
    <JumboComponent/>
    <articleMain/>
    <productMain/>
  </main>

  <footer>
    <footerLink/>
  </footer>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;

</style>
