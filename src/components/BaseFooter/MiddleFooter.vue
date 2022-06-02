<template>
    <footer class="middle-footer">
        <div class="container container-footer-middle">
           <!-- lista di links  -->
            <div class="contact-lists">
                <div class="col">
                    <ul class="col-ul">
                        <h2 class="col-ul-title">DC COMICS</h2>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <ul class="col-ul">
                        <h2 class="col-ul-title">SHOP</h2>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibiles</li>
                    </ul>
                </div>
                <div class="col">
                    <ul class="col-ul">
                        <h2 class="col-ul-title">DC</h2>
                        <li>Terms Of Use</li>
                        <li>Privacy Policy (New)</li>
                        <li>Add Choices</li>
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
                <div class="col">
                    <ul class="col-ul">
                        <h2 class="col-ul-title">SITES</h2>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <!-- parte con il logo dc -->
            <div class="logo-big">
                <img src="../../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'MiddleFooter' ,
}
</script>

<style>
    .middle-footer{
        height: 32.5rem;
        background-image: url(../../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;
    }
    .container-footer-middle{
        display: flex;
        justify-content: space-between;
    }
    .contact-lists{
        display: flex;
        height: 40rem;
        gap: 3rem;
        align-items: flex-start;
        font-size:  1.15rem;
    }
    .col-ul{
        list-style: none;
        display: flex;
        flex-direction: column;
        gap: 0.5rem;
        margin-top: 1rem;
        color: #698887;
    }
    .col-ul-title{
        color: white;
        margin: 1.25rem 0;
    }
    .logo-big img{
        height: 50rem;
        margin: -9rem 0 0 0;
    }
</style>