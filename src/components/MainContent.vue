<template>
    <div class="main">
        <div class="container">
            <div class="card" v-for="(card, index) in cards" :key="index">
                <div>
                    <img class="image" :src="card.thumb" alt="">
                </div>
                <span>{{card.series}}</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MainContent',
    props: {
        cards: Array
    }
}
</script>

<style lang="scss" scoped>
.main{
    background-color: #333;

    .container{
        width: 1200px;
        display: flex;
        margin: 0 auto;
        justify-content: space-around;
        padding: 50px 0;
        flex-wrap: wrap;

        .card{
            width: calc((100% / 6) - 15px);
            height: 185px;
            padding: 15px 0;
            text-align: left;
            color: white;
            margin-bottom: 75px;

            div{
                margin-bottom: 15px;

                .image{
                    width: 100%;
                    max-height: 185px;
                    object-fit: cover;
                }
            }

            span{
                text-transform: uppercase;
                font-size: 12px;
            }
        }
    }
}
</style>