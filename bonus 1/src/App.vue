<script>

import ciaomondo from './components/ciaomondo.vue'; //importo in App.vue la compomponente ciao mondo
import immageComp from './components/immageComp.vue'
export default{
  components:{
    ciaomondo,
    immageComp,
  }
}
</script>

<template>
  <div>
    <ciaomondo/>
    <immageComp/>
  </div>
</template>

<style scoped>

</style>
