<template>
    <header class="container">
        <!-- Logo dell'header -->
        <div class="header-left">
            <img src="../../assets/img/dc-logo.png" alt="Logo di DC Comics">
        </div>
        <!-- Navigazione -->
        <div class="header-right">
            <nav>   
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li class="active"><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibiles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav> 
        </div>
    </header>
</template>

<script>
export default {
    name: 'BaseHeader',
}
</script>

<style lang="scss" scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 2.5rem 0;
        &-right {
            font-weight: 700;
        } ul{
            display: flex;
            list-style: none;
            gap: 1.5rem;
        }a{
            text-decoration: none;
        }
    }
</style>