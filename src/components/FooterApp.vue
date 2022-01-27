<template>
    <footer>
        <div class="footer-container">
            <div class="footer-nav">
                <ul>
                    <li><h3>DC COMICS</h3></li>
                    <li> <a href="#"> Caracters </a></li>
                    <li> <a href="#"> Comics </a></li>
                    <li> <a href="#"> Movies </a></li>
                    <li> <a href="#"> Tv </a></li>
                    <li> <a href="#"> Games </a></li>
                    <li> <a href="#"> Videos </a></li>
                    <li> <a href="#"> News </a></li>
                    
                    <li><h3>SHOP</h3></li>
                    <li> <a href="#"> Shop DC </a></li>
                    <li> <a href="#"> Shop DC Collectibles </a></li>
                </ul>
                <ul>
                    <li><h3>DC</h3></li>
                    <li> <a href="#"> Terms of Use </a></li>
                    <li> <a href="#"> Privacy Policy </a></li>
                    <li> <a href="#"> Ad Choices </a></li>
                    <li> <a href="#"> Advertising </a></li>
                    <li> <a href="#"> Jobs </a></li>
                    <li> <a href="#"> Subscriptions </a></li>
                    <li> <a href="#"> Talent Workshops </a></li>
                    <li> <a href="#"> CPSC Certificates </a></li>
                    <li> <a href="#"> Ratings </a></li>
                    <li> <a href="#"> Shop Help </a></li>
                    <li> <a href="#"> Contact Us </a></li>
                </ul>
                <ul>
                    <li><h3>SITES</h3></li>
                    <li> <a href="#"> DC </a></li>
                    <li> <a href="#"> MAD Magazine </a></li>
                    <li> <a href="#"> DC Kid </a></li>
                    <li> <a href="#"> DC Universe </a></li>
                    <li> <a href="#"> DC Power Visa </a></li>
                </ul>
            </div>
            <div class="logo-img">
                <img src="@/assets/dc-logo-bg.png" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
footer {
    height: 400px;
    background: url(../assets/footer-bg.jpg) no-repeat top;
    background-size: cover;
    .footer-container {
        height: 100%;
        width: 100%;
        display: flex;
        justify-content: space-around;
        .logo-img {
            align-self: center;
        img {
            width: 600px;
        }
        }
        .footer-nav {
            display: flex;
            ul{
                margin: 25px 50px 0 0;
                list-style: none;
                a {
                    text-decoration: none;
                    color: #b9b9b9;
                    line-height: 23px;
                    &:hover {
                        color: $first-txt-color;
                    }
                }
            }
            h3{
                margin: 15px 0;
            }
        }
    }
}
</style>