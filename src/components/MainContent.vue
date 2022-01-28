<template>
    <div class="main">
        <div class="container">
            <div class="row">
                <div class="card" v-for="(card, index) in cards" :key="index">
                    <div>
                        <img class="image" :src="card.thumb" alt="">
                    </div>
                    <span>{{card.series}}</span>
                </div>
            </div>
            <span class="button">LOAD MORE</span>
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
@import '@/style/variables';
.main{
    background-color: #333;

    .container{
        width: 1200px;
        margin: 0 auto;
        padding: 50px 0 25px 0;

        .row{
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-bottom: 50px;

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

        .button{
            color: white;
            width: auto;
            padding: 10px 50px;
            font-size: 12px;
            background-color: $hoverColor;
            cursor: pointer;
        }
    }    
}
</style>