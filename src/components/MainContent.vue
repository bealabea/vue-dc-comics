<template>
    <main>
        <div class="section-title"><h1>current series</h1></div>
        <div class="main-container">
            <div v-for="(card, index) in cards" :key="index" class="cards">
                <div class="card-image">
                    <img :src="card.thumb" alt="">
                </div>
                <div>{{card.series}}</div>
            </div> 
        </div>
        <div class="button-cards">
            <button> LOAD MORE</button>
        </div>
    </main>
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
@import '@/style/main-container.scss';
</style>