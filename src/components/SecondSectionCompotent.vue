<template>
    <div class="blue-section">
        <div class="img-conteiner">
            <div class="card">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="card">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="card">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="card">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="card">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SecondSectionComponent'
}
</script>

<style lang="scss" scoped>
    .blue-section{
        background-color: blue;
        padding: 50px 0px;
    }

    .img-conteiner{
        display: flex;
        justify-content: center;
        max-width: 1200px;
        margin: 0 auto;
        justify-content: space-around;
    }

    .card{
        display: flex;
        align-items: center;
        column-gap: 15px;
        color: white;
        
        img{
            height: 50px;
        }

        span{
            font-size: 0.8rem;
        }
    } 

</style>