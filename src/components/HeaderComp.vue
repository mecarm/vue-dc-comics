<template>
  <header>

    <img src="../assets/img/dc-logo.png" alt="DC logo">
    
    <div> 
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>

  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variabili.scss';

  header{
    @include center;
  }

  header, ul{
    @include justify($justify: Both);
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: bold;
    font-size: 0.9rem;
  }
  ul{
    li{
      list-style: none;
      margin: 10px;
      padding: 20px 0;

      &:hover{
        color: $color-primary;
        border-bottom: 3px solid $color-primary;
      }
    }
  }
</style>
