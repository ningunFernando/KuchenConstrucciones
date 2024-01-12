<script setup>
    import { RouterLink} from 'vue-router'
    // eslint-disable-next-line no-unused-vars
    const primary = ''
</script>

<template>
    <nav>
        <div class="hamburger-container">
            <ion-icon name="reorder-four-outline"></ion-icon>
        </div>
        <div class="logo-container">
            <p class="logo">San Angel</p> 
        </div>
        <div class="links-container">
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
        </div>
    </nav>
</template>

<style scoped>
 nav {
    background-color: var(--primary) ;
    width: 100dvw;
    height: 10dvh;
    display: flex;
    flex-direction: column;
    align-items: center
 }
</style>