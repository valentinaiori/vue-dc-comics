<template>
    <div class="social-footer">
        <div class="button-foot">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="icon-social">
            <h4>FOLLOW US</h4>
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
    name: 'SocialComponent'

}
</script>

<style lang="scss" scoped>
    .social-footer{
        background-color: #303030;
        display: flex;
        align-items: center;
        padding: 30px 0px;
    }

    .button-foot button{
        color: white;
        border: 2px solid #0282f9;
        padding: 10px 15px;
        background-color: #303030;
    }
    .icon-social{
        display: flex;
        align-items: center;
        h4{
            color: #0282f9;
            padding-right: 15px;
            margin-top: 3px;
        };

        img{
            padding-right: 15px;
        }
    }
</style>