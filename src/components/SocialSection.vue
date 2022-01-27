<template>
    <section class="social-bg">
        <div class="footer-social">
            <div>
                <button>SIGN-UP NOW</button>
            </div>
            <div class="social-icons">
                <div>FOLLOW US</div>
                <img src="@/assets/footer-facebook.png" alt="">
                <img src="@/assets/footer-twitter.png" alt="">
                <img src="@/assets/footer-youtube.png" alt="">
                <img src="@/assets/footer-pinterest.png" alt="">
                <img src="@/assets/footer-periscope.png" alt="">
            </div> 
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
.social-bg {
        height: 100px;
        background-color: #333;
        position: relative;
        .footer-social {
            height: 100%;
            width: 80%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            button {
                padding: 10px;
                border: 2px #0282f9 solid;
                outline: none;
                background-color: #333;
                color: $first-txt-color;
            }
            .social-icons {
                display: flex;
                align-items: center;
                div {
                    margin-right: 20px;
                    color: $third-txt-bg-color;
                    font-weight: 700;
                }
                img{
                    margin: 0 10px;
                    cursor: pointer;
                }
            }
        }  
}
</style>