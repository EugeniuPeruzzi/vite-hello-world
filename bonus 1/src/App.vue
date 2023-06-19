<script>

import ciaomondo from './components/ciaomondo.vue'; //importo in App.vue la compomponente ciao mondo
import AppHero from './components/AppHero.vue'
export default{
  components:{
    ciaomondo,
    AppHero,
  }
}
</script>

<template>
  <div>
    <ciaomondo/>
    <AppHero/>
  </div>
</template>

<style scoped>

</style>
