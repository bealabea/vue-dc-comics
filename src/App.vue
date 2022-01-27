<template>
  <div id="app">
    <header-box/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';
</style>
