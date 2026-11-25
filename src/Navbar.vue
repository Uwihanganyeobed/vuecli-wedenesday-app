<script setup>
</script>

<template>
    <div>
        <img src="/images/logo.png"
        alt="">
        <nav>
            <a href="/">Home</a>
            <a href="/products">Products</a>
            <a href="/contact">Contact</a>
            <a href="/login">Login</a>
        </nav>
    </div>
</template>

<style scoped>
div{
    display: flex;
    flex-direction: row;
    margin: 10px;
    padding: 10px;
    align-items: center;
    background-color: green;
    border-radius: 10px;
    top: 0;
    position: sticky;
    justify-content: space-between;
}
img{
    width: 50px;
    height: 50px;
    border-radius: 50%;
}
nav{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-evenly;
    gap: 3rem;
}
a{
    text-decoration: none;
    color: white;
    font-size: 20px;
}
</style>