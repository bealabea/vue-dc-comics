<template>
    <div class="main-container">
        <div v-for="(card, index) in cards" :key="index" class="cards">
            <div class="card-image">
                <img :src="card.thumb" alt="">
            </div>
            <div>{{card.series}}</div>
        </div> 
    </div>
</template>

<script>
export default {
    props: {
        cards: Array
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
@import '@/style/cards-container.scss';
</style>