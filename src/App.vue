<template>
  <div id="app" class="app">
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style lang="stylus">
  .app
    background #000
</style>
