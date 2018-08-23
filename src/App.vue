<template>
  <div class="app">
    Hello
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style lang="scss" module>
    .app {
        composes: app from "./style/app.module.scss";
    }
</style>
