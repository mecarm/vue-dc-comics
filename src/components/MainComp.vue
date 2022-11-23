<template>
    <main>
        <ContentMainComp />

        <ContentMainBlu />

    </main>
</template>

<script>
import ContentMainComp from './ContentMainComp.vue'
import ContentMainBlu from './ContentMainBlu.vue'


export default {
    name: 'MainComp',
    components: {

        ContentMainComp,
        ContentMainBlu
    }
}
</script>

<style lang="scss" scoped>

</style>

