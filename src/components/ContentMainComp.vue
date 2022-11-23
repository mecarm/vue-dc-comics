<template>
  <div class="black">
    <h2> --> Content goes here  </h2>
  </div>
</template>

<script>
export default {
    name: 'ContentMainComp'
}
</script>

<style lang="scss" scoped>

@import "../style/variabili.scss";
    .black{
        background: black;
        text-align: start;
        padding: 40px 0;
        margin-top: 10px;
    }
    h2{
        @include center;
        color: white;
  }
</style>