<template>
    <div class="social-footer">
        <div class="button-foot">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="icon-social">
            <h3>FOLLOW US</h3>
            <img src="../assets/img/footer-facebook.png" alt="Facebook">
            <img src="../assets/img/footer-periscope.png" alt="Periscope">
            <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
            <img src="../assets/img/footer-twitter.png" alt="Twitter">
            <img src="../assets/img/footer-youtube.png" alt="Youtube">
        </div>

    </div>
  
</template>

<script>
export default {
    name: 'SecondFooterComponent'

}
</script>

<style lang="scss" scoped>
    .social-footer{
        background-color: grey;
        display: flex;
        align-items: center;
        padding: 30px 0px;

    }

    .button-foot button{
        color: white;
        border: 1px solid blue;
        padding: 10px 15px;
        background-color: grey;
    }
    .icon-social{
        display: flex;
        align-items: center;
        h3{
            color: blue;
        };
    }
</style>