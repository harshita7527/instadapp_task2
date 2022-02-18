<template>
  <div>
    <AppHeader />
    <hr>
    <TotalAssets />
    <DeFiProtocols />
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader.vue'
import TotalAssets from '../components/TotalAssets.vue'
import DeFiProtocols from '../components/DeFiProtocols.vue'

export default {
  name: 'IndexPage',
  component: {
    AppHeader,
    TotalAssets,
    DeFiProtocols
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  background: rgb(248, 248, 248);
  margin: 0 8rem;
}
</style>
