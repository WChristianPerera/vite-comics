<script>
    export default {};
</script>

<template>
    <footer>

        <div class="f-top">

            <div class="more-info">

                <div class="1_column">
                    <ul>
                        <h1>DC COMICS</h1>

                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <ul>
                        <h1>SHOP</h1>

                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>

                <div class="2_column">
                    <ul>
                        <h1>DC</h1>

                        <li>Term Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>

                <div class="3_column">
                    <ul>
                        <h1>SITES</h1>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
               


                    
            </div>

            <div class="logo">
                <img src="../../vue-dc-comics-1/img/dc-logo-bg.png" alt="">
            </div>

        </div>


        <div class="f-bot">

            <div class="sign-up">
                <div class="btn">SIGN-UP NOW!</div>
            </div>

            <div class="socials">
                <ul>
                    <h1>FOLLOW US</h1>
                    <li><img src="../../vue-dc-comics-1/img/footer-facebook.png" alt=""></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-periscope.png" alt=""></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-pinterest.png" alt=""></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-twitter.png" alt=""></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-youtube.png" alt=""></li>
                </ul>
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
    footer{
        background-image: url(../../vue-dc-comics-1/img/footer-bg.jpg);

        ul{
            gap: 1rem;
        }

        li{
            list-style: none;
        }
    }
    .f-top{
        display: flex;

        .more-info{
            display: flex;
            align-items: start;
        }

        
    }
    
    .f-bot{
        display: flex;
        background-color: #303030;
        padding: 2rem;

        .btn{
            border: 1px solid #0282F9;
            color: white;
            padding: 1rem;
        }
         
        ul{
            display: flex;
        }
    }
      
    
    
</style>