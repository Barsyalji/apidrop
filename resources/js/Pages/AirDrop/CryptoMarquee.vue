<template>
  <!-- Marquee Ticker -->
  <div class="w-full overflow-hidden sticky top-0 left-0 z-50">
    <div class="relative flex w-max animate-marquee">
      <!-- Duplicate for seamless loop -->
      <div
        class="flex whitespace-nowrap text-white text-sm font-medium"
        v-for="i in 2"
        :key="i"
      >
        <span
          v-for="(coin, index) in coins"
          :key="`${index}-${i}`"
          class="inline-block px-6"
        >
          {{ coin.name }}: ${{ coin.price.toFixed(2) }}
          <span
            :class="[
              coin.change >= 0
                ? 'text-green-400 bg-green-400/10'
                : 'text-red-400 bg-red-400/10',
              'px-2 py-1 rounded',
            ]"
          >
            ({{ coin.change >= 0 ? '+' : '' }}{{ coin.change }}%)
          </span>
        </span>
      </div>
    </div>
  </div>

  <!-- Navbar -->
  <div class="container mx-auto px-4  sticky top-[40px] z-40">
    <nav class="w-full flex items-center justify-between px-6 md:px-12 py-4">
      <!-- Logo -->
      <div class="flex items-center gap-2">
        <span class="text-2xl font-bold tracking-tight">
          <img
            src="/images/airdrop-alert-logo.avif"
            alt="Logo"
            class="w-32 md:w-40"
          />
        </span>
      </div>

      <!-- Mobile Menu Button -->
      <div class="md:hidden">
        <button @click="toggleMenu" class="text-white focus:outline-none">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"
            />
          </svg>
        </button>
      </div>

      <!-- Navigation Links -->
      <div
        :class="[
          'md:flex gap-8 text-gray-200 text-sm px-6 md:px-0 py-4 md:py-0',
          showMenu ? 'block' : 'hidden',
          'md:static w-full md:w-auto bg-[#0b101b]/95 md:bg-transparent',
        ]"
      >
        <a href="#" class="block md:inline hover:text-green-400 mb-2 md:mb-0"
          >Home</a
        >
        <a href="#" class="block md:inline hover:text-green-400 mb-2 md:mb-0"
          >Portfolio</a
        >
        <a href="#" class="block md:inline hover:text-green-400 mb-2 md:mb-0"
          >Upgrade</a
        >
        <a href="#" class="block md:inline hover:text-green-400">Docs</a>
      </div>
    </nav>
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

const showMenu = ref(false);
const toggleMenu = () => {
  showMenu.value = !showMenu.value;
};
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
