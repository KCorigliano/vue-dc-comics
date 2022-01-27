<template>
    <div class="header">
        <div class="header-logo">
            <img src="@/assets/dc-logo.png" alt="">
        </div>
        <div class="header-right">
            <span>CHARACTERS</span>
            <span>COMICS</span>
            <span>MOVIES</span>
            <span>TV</span>
            <span>GAMES</span>
            <span>COLLECTIBLES</span>
            <span>VIDEOS</span>
            <span>FANS</span>
            <span>NEWS</span>
            <span>SHOP</span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeaderBox',
}
</script>

<style lang="scss" scoped>

.header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 1200px;
    margin: 0 auto;

    .header-right{

        span{
            padding: 5px 15px;
        }
    }
}

</style>