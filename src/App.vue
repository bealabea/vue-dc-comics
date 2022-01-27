<template>
  <div id="app">
    <header-box/>
    <jumbo-container/>
    <main-content/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboContainer from './components/JumboContainer.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboContainer,
    MainContent
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';
</style>
