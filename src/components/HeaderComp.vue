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

  header{
    width: 80%;
    margin: auto;
  }

  header, ul{
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: bold;
    font-size: 0.8rem;
  }
  ul{
    li{
      list-style: none;
      margin: 10px;
      padding: 20px 0;

      &:hover{
        color: #0E7CEB;
        border-bottom: 3px solid #0E7CEB ;
      }
    }
  }
</style>
