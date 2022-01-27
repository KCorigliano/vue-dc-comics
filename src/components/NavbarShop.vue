<template>
    <div class="navbar">
        <div class="container">
            <div>
                <img src="@/assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div>
                <img src="@/assets/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
            </div>
            <div>
                <img src="@/assets/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTION</p> 
            </div>
            <div>
                <img src="@/assets/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p> 
            </div>
            <div>
                <img src="@/assets/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p> 
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'NavbarShop',
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.navbar{
    background-color: $hoverColor;

    .container{
        width: 1200px;
        display: flex;
        align-items: center;
        justify-content: space-around;
        margin: 0 auto;
        padding: 30px 0;

        > div{
            display: flex;
            align-items: center;
            color: white;
            font-weight: bold;
            cursor: pointer;
            
                img{
                    width: 50px;
                    margin-right: 15px;
                }
        }
    }
}

</style>