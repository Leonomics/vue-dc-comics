<template>
    <footer>
        <div class="productsAndShopsWrapper">
            <ul class="productsAndShops container">
            <li class="imgAndText">
                <img class="buyImg" src="../vue-dc-comics-1/img/buy-comics-digital-comics.png">
                <h3 class="buyTitle">
                    DIGITAL COMICS
                </h3>
            </li>
            <li class="imgAndText">
                <img class="buyImg" src="../vue-dc-comics-1/img/buy-comics-digital-comics.png">
                <h3 class="buyTitle">
                    DIGITAL COMICS
                </h3>
            </li>
            <li class="imgAndText">
                <img class="buyImg" src="../vue-dc-comics-1/img/buy-comics-digital-comics.png">
                <h3 class="buyTitle">
                    DIGITAL COMICS
                </h3>
            </li>
            <li class="imgAndText">
                <img class="buyImg" src="../vue-dc-comics-1/img/buy-comics-digital-comics.png">
                <h3 class="buyTitle">
                    DIGITAL COMICS
                </h3>
            </li>
            <li class="imgAndText">
                <img class="buyImg" src="../vue-dc-comics-1/img/buy-comics-digital-comics.png">
                <h3 class="buyTitle">
                    DIGITAL COMICS
                </h3>
            </li>
        </ul>
        </div>
        <div class="footerBiggerSection">
            <div class="footerBiggerWrapper container">
                <div class="columnsWrapper">
                <div class="dCComicsAndShopWrapper">
                    <div class="dCComics">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li></li>
                        </ul>
                    </div>
                    <div class="shop">
                        <h3>SHOP</h3>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC collectibles</li>
                        </ul>
                    </div>
                </div>
                <div class="dC">
                    <h3>DC</h3>
                    <ul>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                    </ul>
                </div>
                <div class="sites">
                    <h3>SITES</h3>
                    <ul>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                        <li>lorem</li>
                    </ul>
                </div>
            </div>
            <div class="bigDCLogo">
            
            </div>
            </div>
            
        </div>
        <div class="socialFooter">
            <div class="socialFooterWrapper container">
                    <button class="signUpButton">SIGN-UP NOW</button>
                    <div class="socialIcons">
                    <h3 class="followUs">FOLLOW US</h3>
                    <img class="socialIcon" src="../vue-dc-comics-1/img/footer-facebook.png" alt="">
                    <img class="socialIcon" src="../vue-dc-comics-1/img/footer-twitter.png" alt="">
                    <img class="socialIcon" src="../vue-dc-comics-1/img/footer-youtube.png" alt="">
                    <img class="socialIcon" src="../vue-dc-comics-1/img/footer-pinterest.png" alt="">
                    <img class="socialIcon" src="../vue-dc-comics-1/img/footer-periscope.png" alt="">
                    </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default{
        name: 'FooterItem',
    }
</script>

<style scoped lang="scss">
    main{
        background-color: black;
        color: white;
        height: 130px;
    }
    .productsAndShops{
        display: flex;
    }
    .imgAndText{
        display: flex;
        align-self: center;
    }
    .productsAndShopsWrapper{
        background-color: #0282f9;
    }
    .buyImg{
        height: 64px;
        width: 32px;
        margin-right: 16px;
        margin-top: 48px;
        margin-bottom: 48px;
    }
    h3{
        align-self: center;
    }
    .footerBiggerSection{
        background-image: url("../vue-dc-comics-1/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }
    .footerBiggerWrapper{
        display: flex;
        justify-content: space-between;
    }
    .dCComicsAndShopWrapper{
        display: flex;
        justify-content: flex-start;
        flex-direction: column;
        margin-right: 52px;
    }
    .columnsWrapper{
        display: flex;
        justify-content: flex-start;
        flex-direction: row;
        text-align: left;
        color: white;
    }
    .dC{
        margin-right: 52px;
        margin-top: 40px;
    }
    .dCComics{
        margin-bottom: 24px;
        margin-top: 40px;
    }
    .sites{
        margin-top: 40px;
    }
    .shop{
        margin-bottom: 40px;
    }
    .socialFooter{
        background-color: #303030;
    }
    .signUpButton{
        background-color: transparent;
        padding: 16px;
        border: 2px solid #0282f9;
        margin-top: 30px;
        margin-bottom: 30px;
    }
    .socialFooterWrapper{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    .socialIcons{
        display: flex;
    }
    .socialIcon:not(:last-child){
        margin-right: 14px;
    }
    .socialIcon{
        width:32px;
        height: 32px;
        align-self: center;
    }
    .followUs{
        margin-right: 14px;
        color:#0282f9;
    }
    .buyTitle{
        color: white;
        font-size: 1rem;
        margin-right: 72px;
        white-space: nowrap;
    }
    .bigDCLogo{
        height: 120%;
        background-image: url(../vue-dc-comics-1/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: center;
        height: 400px;
        width: 800px;
        background-size: auto 130%;
    }
    
</style>