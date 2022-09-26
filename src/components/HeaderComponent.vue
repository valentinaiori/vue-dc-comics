<template>
    <div class="contenitor">
        <div>
            <img src="../assets/img/dc-logo.png" alt="dc-logo">
        </div>
        <div>
            <ul class="list">
                <li><a href="">CHARACTERS</a></li>
                <li><a href="">COMICS</a></li>
                <li><a href="">MOVIES</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAMES</a></li>
                <li><a href="">COLLECTION</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeaderComponent'
}
</script>

<style lang="scss" scoped>
    .contenitor{
        display: flex;
        justify-content: space-between;
        align-items: center;



    .list{
        display: flex;
        list-style-type: none;

        li{
            padding: 0px 10px;
            
            a{
                text-decoration: none;
                color: black;
                font-size: 0.8rem;
            }
        }
    }
    }
    img{
        margin-top: 20px;
        margin-bottom: 20px;
        padding-right: 110px;
    }
</style>