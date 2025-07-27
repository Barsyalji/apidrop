<script setup>
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
import { Link } from '@inertiajs/vue3';
import CryptoMarquee from '@/Pages/AirDrop/CryptoMarquee.vue';
import Topbar from '@/Components/Menu/Topbar.vue';
import Footer from '@/Components/Menu/Footer.vue';
</script>

<template>
    <div
    >
            <CryptoMarquee />
        <Topbar />

        <div
            class=""
        >
            <slot />
                <Footer />
        </div>
    </div>
</template>
