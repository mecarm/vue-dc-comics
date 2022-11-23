<template>
  <div class="container">
    <div>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital comics">
        <div>DIGITAL COMICS</div>
    </div>
    <div>
        <img src="../assets/img/buy-comics-merchandise.png" alt="Digital comics">
        <div>DC MERCHANDISE</div>
    </div>
    <div>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="Digital comics">
        <div>SUBSCRIPTION</div>
    </div>
    <div>
        <img src="../assets/img/buy-comics-shop-locator.png" alt="Digital comics">
        <div>COMIC SHOP LOCATOR</div>
    </div>
    <div>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="Digital comics">
        <div>DC POWER VISA</div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'ContentMainBlu'
}
</script>

<style lang="scss" scoped>
@import '../style/variabili.scss';
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: $color-primary;
    padding: 50px 0;

    div{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0 15px;
        font-size: 0.8rem;
        color: white;
        font-family: Verdana, Geneva, Tahoma, sans-serif;

        img{
            height: 50px;
            max-width: 50px;
        }
    }
}

</style>