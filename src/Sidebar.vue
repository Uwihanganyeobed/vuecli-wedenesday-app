<script setup> 
const sidebarLInks = ['Dashboard',
 'Users','Products','Reports','Logout']
</script>
<template>
    <div class="side">
        <div v-for="link in sidebarLInks">
            <p>{{ link }}</p>
        </div>
    </div>
</template>
<style scoped>
.side{
    background-color: rgb(26, 99, 128);
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 2rem;
    flex: 0.2;
border-radius: 20px;
}
.side p{
    color: aliceblue;
    font-size: larger;
    font-family: serif;
}
</style>

