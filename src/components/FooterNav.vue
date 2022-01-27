<template>
    <div class="footer-navbar">
        <div class="container">
            <div class="footer-navbar-left">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="footer-navbar-right">
                <div>
                    <p>FOLLOW US</p>
                </div>
                <div>
                    <img src="@/assets/footer-facebook.png" alt="">
                    <img src="@/assets/footer-twitter.png" alt="">
                    <img src="@/assets/footer-youtube.png" alt="">
                    <img src="@/assets/footer-pinterest.png" alt="">
                    <img src="@/assets/footer-periscope.png" alt="">
                </div>
                
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterNav',
}
</script>

<style lang="scss" scoped>
@import '@/style/variables';

.footer-navbar{
    background-color: #333;

    .container{
        display: flex;
        justify-content: space-between;
        align-content: center;
        width: 1200px;
        margin: 0 auto;

        > div{
            width: 50%;
            padding: 30px 0;
        }

        .footer-navbar-left{
            display: flex;

            button{
                margin: auto 0;
                color: white;
                background: #333;
                font-weight: bold;
                border: 2px solid $hoverColor;
                padding: 15px;
                cursor: pointer;
            }
        }

        .footer-navbar-right{
            display: flex;
            justify-content: end;

            > div{
                display: flex;
                align-content: center;
            }

            p{
                color: $hoverColor;
                font-weight: bold;
                margin: auto 15px;
            }

            img{
                margin: auto 0 auto 15px;
                cursor: pointer;
            }
        }
    }
}
</style>