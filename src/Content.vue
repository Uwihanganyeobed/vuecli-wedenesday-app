<script setup>
</script>

<template>
    <div class="center">
        <div class="card">
            <img src="/images/logo.png" alt="">
            <h2>high end sneaker</h2>
            <p>price</p>
            <div class="cart">
                <button>-</button>
                <button> cart</button>
                <button>+</button>
            </div>
        </div>
         <div class="card">
            <img src="/images/logo.png" alt="">
            <h2>high end sneaker</h2>
            <p>price</p>
            <div class="cart">
                <button>-</button>
                <button> cart</button>
                <button>+</button>
            </div>
        </div>
         <div class="card">
            <img src="/images/logo.png" alt="">
            <h2>high end sneaker</h2>
            <p>price</p>
            <div class="cart">
                <button>-</button>
                <button> cart</button>
                <button>+</button>
            </div>
        </div>
         <div class="card">
            <img src="/images/logo.png" alt="">
            <h2>high end sneaker</h2>
            <p>price</p>
            <div class="cart">
                <button>-</button>
                <button> cart</button>
                <button>+</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.center {
    display: flex;
    flex: 0.8;
}
.card{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    background-color: rgb(214, 208, 208);
    padding: 10px;
    border-radius: 20px;
    margin-left: 20px;
}
.card img{
    width: 100px;
    border-radius: 20px;
}
.card h2{
    color: rgb(5, 5, 5);
    font-family: Arial, Helvetica, sans-serif;
    font-size: medium;
}
.card p{
    color: rgb(0, 0, 0);
    font-size: medium;
}
.cart{
padding: 1rem;
display: flex;
flex-direction: row;
align-items: center;
gap:10px ;
}.cart button{
    color: aliceblue;
    width: 100%;
    background-color:rgb(56, 163, 156);
    border-radius: 10px;
    padding: 10px;
    border: none;
}
</style>