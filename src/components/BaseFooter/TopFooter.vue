<template>
    <footer class="top-footer">
        <div class="container-small">
            <ul class="footer-ul" >
                <li><img src="../../assets/img/buy-comics-digital-comics.png" alt=""><a href="#">Digitals Comics</a></li>
                <li><img src="../../assets/img/buy-comics-merchandise.png" alt=""><a href="#">DC Mercahndise</a></li>
                <li><img src="../../assets/img/buy-comics-subscriptions.png" alt=""><a href="#">Subscription</a></li>
                <li><img src="../../assets/img/buy-comics-shop-locator.png" alt=""><a href="#">Comic Shop Locator</a></li>
                <li><img src="../../assets/img/buy-dc-power-visa.svg" alt=""><a href="#">DC Power Visa</a></li>
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
        height: 25rem;
        background-color: var(--primary-color);
        display: flex;
        align-items: center;
    }

    .footer-ul{
        display: flex;
        justify-content: space-between;
        align-items: center;
        list-style: none;
        text-transform: uppercase;  
        gap: 5rem;
    }
    .footer-ul li{
        display: flex;
        align-items: center;
        gap: 1rem;
    }
    .footer-ul a{
        text-decoration: none;
        color: white;
    }
</style>