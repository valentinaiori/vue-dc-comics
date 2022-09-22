<template>
    <div class="footer">
        <div class="list-link">
            <div class="content-list-link">
                <h3>DC COMICS</h3>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <h3>SHOP</h3>
                <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="content-list-link">
                <h3>DC</h3>
                <ul>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div class="content-list-link">
                <h3>SITES</h3>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
        <div class="logo-footer">
            <img src="../assets/img/dc-logo-bg.png" alt="logo-bg">
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterComponent'

}
</script>

<style lang="scss" scoped>
    .footer{
        background-image: url(../assets/img/footer-bg.jpg);
        display: flex;
        justify-content: space-around;
        color: white;
    }

    .logo-footer img{
        width: 70%;
    }

    .list-link{
        display: flex;
        li{
            list-style-type: none;
            padding: 5px 0px;
            
            a{
                color: white;
                text-decoration: none;
                font-size: 0.8rem;
            }
        };

        .content-list-link{
            padding: 20px 30px;
            h3{
                padding: 15px 0px;
            }
        }
    }
</style>