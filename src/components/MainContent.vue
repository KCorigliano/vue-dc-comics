<template>
    <div class="main">
        <div class="container">
            <span class="info-span">CURRENT SERIES</span>
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
@import '@/style/mainContent'
</style>