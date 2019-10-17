<template>
  <div id="app">
    <div id="nav">
      Hi, I can change it
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@import url('helpers/reset.scss');
</style>
