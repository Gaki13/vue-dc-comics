<template>
    <div class="card">
        <img :src="img" alt="series">
        <h3 class="card-title">{{series}}</h3>
    </div>
</template>

<script>
export default {
    name: 'CardElement',
    props: {
        img : String,
        series : String
    }  
}
</script>

<style lang="scss" scoped>
    .card{
        img{
            width: 100%;
            height: 246px;
            object-fit: cover;
            object-position: top;
        }
        h3{
            color: white;
        }
    }
</style>