<script setup>
import CryptoMarquee from '@/Pages/AirDrop/CryptoMarquee.vue';
import Footer from '@/Components/Menu/Footer.vue';
</script>
<template>
    <div>
        <CryptoMarquee />
        <div class="">
            <slot />
            <Footer />
        </div>
    </div>
</template>
