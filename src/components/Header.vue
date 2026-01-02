<script setup>
    import logo from '../../public/logo.png'
</script>

<template>
    <header>
        <img :src="logo" alt="Logo">
        <h1>Hi, I'm <span class="highlight">Vue</span></h1>
    </header>
</template>

<style scoped>
    span.highlight {
        color: #40b883;
    }
    header img {
        height: 80px;
    }
    header h1 {
        font-size: 2rem;
        color: #34495e;
        margin-top: 10px;
    }
</style>