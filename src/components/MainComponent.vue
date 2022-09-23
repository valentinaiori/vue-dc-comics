<template>
    <div class="black">
        <div class="text-section">
            <p> --- Content goes here ---</p>
        </div>
        
    </div>
  
</template>

<script>
export default {
    name:'SectionMainComponent'

}
</script>

<style lang="scss" scoped>
    .black{
        background-color: black;
        height: 100px;
    }

    .text-section{
        max-width: 1200px;
        margin: 0 auto;
    }

    p{
        color: white;
        font-size: 1.5rem;
    }

</style>