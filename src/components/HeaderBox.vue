<template>
    <div class="header">
        <nav>
            <div class="header-logo">
                <img src="@/assets/dc-logo.png" alt="">
            </div>
            <div class="header-text">
                <div><span>CHARACTERS</span></div>
                <div><span>COMICS</span></div>
                <div><span>MOVIES</span></div>
                <div><span>TV</span></div>
                <div><span>GAMES</span></div>
                <div><span>COLLECTIBLES</span></div>
                <div><span>VIDEOS</span></div>
                <div><span>FANS</span></div>
                <div><span>NEWS</span></div>
                <div><span>SHOP</span></div>
            </div>
        </nav>
        <div class="jumbotron"></div>
    </div>
</template>

<script>
export default {
    name: 'HeaderBox',
}
</script>

<style lang="scss" scoped>

@import '@/style/headerBox.scss'

</style>