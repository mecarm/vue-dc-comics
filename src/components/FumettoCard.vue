<template>
    <div class="card">
        <img :src="dettagliFumetto.thumb" alt="">
        <h4>{{ dettagliFumetto.series }}</h4>
    </div>
</template>

<script>
export default {
    name: 'FumettoCard',
    props: {
        dettagliFumetto: Object
    }
}
</script>

<style lang="scss" scoped>

    .card{
        width: calc(100% / 6);
        padding: 10px;
        cursor: pointer;
        
        img{
            width: 100%;
        }
    }
</style>