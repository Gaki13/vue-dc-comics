<template>
    <footer class="top-footer">
        <div class="container-small">
            <ul class="footer-ul" >
                <li><a href="#"><img src="../../assets/img/buy-comics-digital-comics.png" alt="">Digitals Comics</a></li>
                <li><a href="#"><img src="../../assets/img/buy-comics-merchandise.png" alt=""> DC Mercahndise</a></li>
                <li><a href="#"><img src="../../assets/img/buy-comics-subscriptions.png" alt=""> Subscription</a></li>
                <li><a href="#"><img src="../../assets/img/buy-comics-shop-locator.png" alt=""> Comic Shop Locator</a></li>
                <li><a href="#"><img src="../../assets/img/buy-dc-power-visa.svg" alt=""> DC Power Visa</a></li>
            </ul>
        </div>       
    </footer>
</template>

<script>
export default {
    name: 'TopFooter' ,
}
</script>

<style>
    .top-footer{
        height: 20rem;
        background-color: var(--primary-color);
        display: flex;
        align-items: center;
    }

    .footer-ul{
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        list-style: none;
        text-transform: uppercase;  
    }
    .footer-ul li{
       align-items: center;
        gap: 3.5rem;
    }
    .footer-ul a{
        display: flex;
        align-items: center;
        text-decoration: none;
        color: white;
        gap: 1.5rem;
    }
</style>