<template>
    <div class="card">
        <img :src="dettagliFumetto.thumb" alt="">
        <h5>{{ dettagliFumetto.series }}</h5>
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
.card {
    width: calc(100% / 6);
    padding: 10px;
    cursor: pointer;

    img {
        width: 100%;
        aspect-ratio: 1/1;
        object-fit: cover;
        object-position: top;
    }
}
</style>