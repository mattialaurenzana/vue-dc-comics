<template>
    
    <header>
        <div class="header-left">
            <img src="../assets/dc-logo.png" alt="">
        </div>

        <div class="header-right">
            <ul>
               <li v-for="item in list" :key="item"><a href="">{{item}}</a></li>
            </ul>

        </div>
    </header>

</template>





<script>
export default {
    props:{
        list: Array
    }
}
</script>



<style lang="scss" scoped>
    @import '../style/header.scss'
</style>