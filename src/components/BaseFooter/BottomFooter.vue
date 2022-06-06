<template>
    <footer class="bottom-footer">
        <div class="container container-footer-bottom">
            <!-- sezione per il sign up -->
            <div class="sign-up">
                <button class="sign-up-btn">
                    SIGN-UP NOW!
                </button>
            </div>
            <!-- sezione per i social -->
            <div class="social">
                <h2 class="social-title">FOLLOW US</h2>
                <a href="#"><img src="../../assets/img/footer-facebook.png" alt="icona di facebook"></a>
                <a href="#"><img src="../../assets/img/footer-twitter.png" alt="icona di twitter"></a>
                <a href="#"><img src="../../assets/img/footer-youtube.png" alt="icona di youtube"></a>
                <a href="#"><img src="../../assets/img/footer-pinterest.png" alt="icona di pinterest"></a>
                <a href="#"><img src="../../assets/img/footer-periscope.png" alt="icona di periscope"></a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'BottomFooter'
}
</script>

<style>
    .bottom-footer{
        height: 10rem;
        background-color: var(--footer-color);
    }
    .container-footer-bottom {
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
   .social{
       display: flex;
       gap: 1.5rem;
   }
   .social-title{
        color: #0282f9;
    }
    .sign-up-btn{
    padding: 1rem;
    font-size: 1.5rem;
    background-color: inherit;
    border: 3px solid #0282f9;
    color: white;
    transition: background-color;
    }

    .sign-up-btn:hover{
        background-color: #0282f9;
        cursor: pointer;
    }
</style>