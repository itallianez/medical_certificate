<template>
  <div id="app">
    <appHeader></appHeader>
    <router-view/>
  </div>
</template>
<script>
  import appHeader from "./components/header";

  export default {
    name: 'home',
    components: {
      appHeader
    }
  }
</script>
<style lang="scss">
@import url('helpers/reset.scss');
</style>
