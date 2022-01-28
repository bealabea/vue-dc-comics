<template>
  <div id="app">
    <header-box :nav="nav"/>
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
  },
  data(){
    return{
      nav: [
        {
          id:'5qYS5oUTVu',
          label: 'Caracters',
          url: '/'
        },
        {
          id:'YsU3URmXbu',
          label: 'Comics',
          url: '/'
        },
        {
          id:'GzKNJfkaHX',
          label: 'Movies',
          url: '/'
        },
        {
          id:'oI5s8dyKWT',
          label: 'Tv',
          url: '/'
        },
        {
          id:'uqk3rcAYFP',
          label: 'Games',
          url: '/'
        },
        {
          id:'XA7RoQ4Gfn',
          label: 'Videos',
          url: '/'
        },
        {
          id:'1NqhGHvcR3',
          label: 'Fans',
          url: '/'
        },
        {
          id:'ftQLeScsea',
          label: 'News',
          url: '/'
        },
        {
          id:'JON0yi8Lly',
          label: 'Shop',
          url: '/'
        },
      ]
    }
  }

}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';
</style>
