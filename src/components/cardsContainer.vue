<template>
    <div class="cards">
        <span class="card-button current">CURRENT SERIES</span>
        <div class="container">
            <div class="card" v-for="(card,index) in cards" :key="index">
                <div class="img-container">
                    <img :src="card.thumb" alt="comic book">
                </div>
                <span>{{card.series}}</span>
            </div>
            <span class="card-button">LOAD MORE</span>
        </div>
    </div>
</template>


<script>
export default {
    props:{
        cards:Array
    }
}
</script>

<style lang="scss" scoped>
    @import '../style/cards.scss'
</style>