<template>
    <div class="w-full bg-gray-900 overflow-hidden sticky top-0 left-0 z-50">
        <div class="relative flex w-max animate-marquee">
            <!-- Duplicate for seamless loop -->
            <div class="flex whitespace-nowrap text-white text-sm font-medium" v-for="i in 2" :key="i">
                <span v-for="(coin, index) in coins" :key="index + '-' + i" class="inline-block px-6">
                    {{ coin.name }}: ${{ coin.price.toFixed(2) }}
                    <span :class="[
                        coin.change >= 0
                            ? 'text-green-400 bg-green-400/10'
                            : 'text-red-400 bg-red-400/10',
                        'px-2 py-1 rounded'
                    ]">
                        > ({{ coin.change >= 0 ? '+' : '' }}{{ coin.change }}%)
                    </span>
                </span>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const coins = ref([
    { name: 'Bitcoin', price: 67290.25, change: 2.5 },
    { name: 'Ethereum', price: 3920.1, change: -1.2 },
    { name: 'BNB', price: 495.12, change: 0.9 },
    { name: 'Solana', price: 170.34, change: 1.8 },
    { name: 'Dogecoin', price: 0.087, change: -0.3 },
    { name: 'XRP', price: 0.59, change: 0.6 },
    { name: 'Litecoin', price: 95.88, change: -0.5 },
    { name: 'Cardano', price: 0.42, change: 2.1 },
]);
</script>

<style scoped>
@keyframes scroll-left-loop {
    0% {
        transform: translateX(0%);
    }

    100% {
        transform: translateX(-50%);
    }
}

.animate-marquee {
    animation: scroll-left-loop 25s linear infinite;
}
</style>
