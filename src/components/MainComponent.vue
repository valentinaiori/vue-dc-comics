<template>
    <div class="black">
        <div class="jumbotron">
            <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
        </div>
        <div class="card-container">
            <div class="card" v-for="card in cards" :key="card.thumb">
                <img :src="card.thumb"/>
                <p>{{card.series}}</p>
            </div>

        </div>
    </div>
  
</template>

<script>
export default {
    name:'MainComponent',

    props: {
        cards: Array,
    }

}
</script>

<style lang="scss" scoped>

    .black{
        background-color: black;
    }

    .jumbotron img{
        width: 100%;
        height:200px;
        position: static;
    }

    .card-container{
        width: 1000px;
        display: flex;
        flex-wrap: wrap;
        padding-bottom: 50px;
    }

    .card{
        flex-direction: column;

        img{
            width: 150px;
            height: 270px;
            padding-top: 50px;
            padding-bottom: 30px;
        }

        p{
        color: white;
        font-size: 0.8rem;
    }
    }

    

</style>