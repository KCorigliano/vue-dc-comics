<template>
    <div class="header">
        <nav>
            <div class="header-logo">
                <img src="@/assets/dc-logo.png" alt="">
            </div>
            <div class="header-text">
                <div v-for="link in nav" :key="link.id"><a :href="link.url"><span>{{link.name}}</span></a></div>
            </div>
        </nav>
        <div class="jumbotron"></div>
    </div>
</template>

<script>
export default {
    name: 'HeaderBox',
    props: {
        nav: Array
    }
}
</script>

<style lang="scss" scoped>

@import '@/style/headerBox.scss'

</style>