<template>
    <div class="last-container">
        <div class="last-inner">
            <span class="sign">SIGN-UP NOW!</span>
            <div class="last-right">
                <span class="follow">FOLLOW US</span>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>
    .last-container{
        height: 100px;
        background-color: rgb(46, 43, 43);

        .last-inner{
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 70%;
            height: 100%;
            margin: 0 auto;

            .sign{
                color: white;
                 padding: 10px;
                border: 2px blue solid;
            }
            .follow{
                font-weight: bold;
                color: rgb(45, 45, 218);
            }

            .last-right{
                display: flex;
                align-items: center;
                gap: 15px;
            }
        }
    }
</style>