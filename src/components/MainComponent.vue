<template>
    <div class="black">
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

    .card-container{
        width: 1000px;
        display: flex;
        flex-wrap: wrap;
        padding-bottom: 50px;
    }

    .card{
        flex-direction: column;
        padding-right: 20px;

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