<template>
  <div id="app">
    <header-box/>
    <jumbo-container/>
    <main-content/>
    <info-shop/>
    <footer-app/>
    <social-section/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboContainer from './components/JumboContainer.vue'
import MainContent from './components/MainContent.vue'
import InfoShop from './components/InfoShop.vue'
import FooterApp from './components/FooterApp.vue'
import SocialSection from './components/SocialSection.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboContainer,
    MainContent,
    InfoShop,
    FooterApp,
    SocialSection
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';
</style>
