<template>
    <main>
        <div class="section-title"><h1>current series</h1></div>
        <cards-container :cards="cards"/>
        <div class="button-cards">
            <button> LOAD MORE</button>
        </div>
    </main>
</template>

<script>
import CardsContainer from '@/components/CardsContainer.vue'
export default {
    components: {
        CardsContainer
    },
    props: {
        cards: Array
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
main {
  background-color: $second-txt-bg-color;
  color: $first-txt-color;
    .section-title {
        position: relative;
        top: -25px;
        left: 200px;
        width: 300px;
        padding: 10px;
        background-color: $third-txt-bg-color;
        text-transform: uppercase;
        text-align: center;
    }
    .button-cards {
        text-align: center;
        padding: 20px;
        button {
            padding: 10px 50px;
            border: none;
            background-color: #0282f9;
            color: $first-txt-color;
            cursor: pointer;
        }
    }
}
</style>