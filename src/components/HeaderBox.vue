<template>
    <header>
        <img src="@/assets/dc-logo.png" alt="">
        <nav>
            <ul>
                <li> <a href="#"> Caracters </a></li>
                <li> <a href="#"> Comics </a></li>
                <li> <a href="#"> Movies </a></li>
                <li> <a href="#"> Tv </a></li>
                <li> <a href="#"> Games </a></li>
                <li> <a href="#"> Videos </a></li>
                <li> <a href="#"> Fans </a></li>
                <li> <a href="#"> News </a></li>
                <li> <a href="#"> Shop </a></li>
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
            a{
                text-decoration: none;
                text-transform: uppercase;
                padding: 36px 20px;
                color: $second-txt-bg-color;
                cursor: pointer;
                &:hover{
                    color: $third-txt-bg-color;
                    border-bottom: 5px #0282f9 solid;
                    font-weight: 700;
                }
            }
    }
    }
    
}
</style>