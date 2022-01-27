<template>
    <header>
        <img src="@/assets/dc-logo.png" alt="">
        <nav>
            <ul>
                <li>CARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
header {
    width: 80%;
    height: 100px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    img {
        padding: 20px;
        height: 100%;
    }
    nav {
        ul {
            list-style: none;
            display: flex;
            align-items: center;
            li{
                padding: 25px 10px;
                color: $second-txt-bg-color;
                cursor: pointer;
                &:hover{
                    color: $third-txt-bg-color;
                    border-bottom: 4px #0282f9 solid;
                }
            }
    }
    }
    
}
</style>