<template>
  <footer>
    <div class="footer-bg">
        <div class="list">
            <div>
                <ul>
                    <h3>DC COMICS</h3>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <h3>DC COMICS</h3>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div>
                <ul>
                    <h3>DC</h3>
                    <li>Term Of Use</li>
                    <li>Privacy Policy(New)</li>
                    <li>Ad Choises</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subiscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div>
                <ul>
                    <h3>SITES</h3>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
        <div class="dc-bg">
            <!-- <img src="../assets/img/dc-logo-bg.png" alt=""> -->
        </div>
        
    </div>
    <div class="social">
        <div>
            <div>
                <button>SIGN UP NOW!</button>
            </div>
            <div class="follow">
                <div>
                    <strong>FOLLOW US</strong>
                </div>
                <div class="icon">
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>

export default {
    name: 'FooterComp'
}
</script>

<style lang="scss" scoped>

@import '../style/variabili.scss';

footer{
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;


    .footer-bg {
        @include center;
        @include justify($justify: Both);

    }

    .list{
        @include justify($justify: Between);
        text-align: start;
        color: white;
        padding: 20px 0;

        h3{
            margin: 10px 0;   
        }
        
        li{
            list-style: none;
            color: lightgray;
            margin-right: 20px ;
            font-size: 0.8rem;
            line-height: 22px;
            cursor: pointer;
        }
    }

.dc-bg{
    background-image: url('../assets/img/dc-logo-bg.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;        
    width: 50%;
    height: 350px;
}
    .social{
        background: rgb(44, 44, 44);
        padding: 30px;
        
        div:first-child{
            @include justify($justify: Between);
            @include center;
    }
     .follow, .icon{
        @include justify($justify: Both);
    }
    .follow{
        div:first-child{
            margin-right: 5px;
            color: $color-primary;
            width: 100px;
        }

        div:last-child > img{
            margin: 0 5px;
        }
    }
}
}
button{
    padding: 10px;
    border: 2px solid $color-primary;
    background-color: rgba(0, 0, 0, 0);
    color: white;
}
</style>