<template>
  <div class="hero">
        <div class="container">
            <h2>CURRENT SERIES</h2>
        </div>
  </div>
  
</template>

<script>
export default {
    name: 'ComponentJumbo'
}
</script>

<style lang="scss" scoped>
    .hero{
        width: 100%;
        height: 35rem;
        background-image: url(../../assets/img/jumbotron.jpg);
        background-repeat: no-repeat;
        background-size: cover;
       .container{
           height: 100%;
           display: flex;
           align-items: flex-end;
           h2{
               color: white;
               background-color: var(--primary-color);
               padding: 15px 25px;
               margin-bottom: -25px;
           }
       }
    }
</style>