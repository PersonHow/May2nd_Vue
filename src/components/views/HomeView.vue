<script setup>
import Card from "./Card.vue";
</script>



<template>
    <main class="homeArea">
        <Card />
        <Card />
        <Card />
    </main>

    
</template>


<style>
.homeArea{
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    /* 畫面延展 */
    flex-grow: 1;
    background-color: rgb(252, 234, 161);
}


</style>