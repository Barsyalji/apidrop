<template>
    <div class="container mx-auto px-4">


       <nav class="sticky top-0 left-0 w-full z-49 flex items-center justify-between px-6 md:px-12 py-4">
                     <div class="flex items-center gap-2">
                         <span class="text-2xl font-bold tracking-tight">
                                                        <img src="/images\airdrop-alert-logo.avif" alt="" srcset="" class="w-1/4">

                         </span>
                     </div>

                     <!-- Mobile Menu Button -->
                     <div class="md:hidden">
                         <button @click="toggleMenu" class="text-white focus:outline-none">
                             <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                                 stroke="currentColor">
                                 <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                     d="M4 6h16M4 12h16M4 18h16" />
                             </svg>
                         </button>
                     </div>

                     <!-- Links -->
                     <div :class="['md:flex gap-8 text-gray-200 text-sm', showMenu ? 'block' : 'hidden']"
                         class="absolute md:static top-full left-0 w-full md:w-auto bg-[#0b101b]/95 md:bg-transparent px-6 md:px-0 py-4 md:py-0">
                         <a href="#" class="block md:inline hover:text-green-400 mb-2 md:mb-0">Home</a>
                         <a href="#" class="block md:inline hover:text-green-400 mb-2 md:mb-0">Portfolio</a>
                         <a href="#" class="block md:inline hover:text-green-400 mb-2 md:mb-0">Upgrade</a>
                         <a href="#" class="block md:inline hover:text-green-400">Docs</a>
                     </div>
                 </nav>

    </div>

</template>
<script>
import { ref, onMounted, onUnmounted } from 'vue';

export default {
    name: "Index",
    components: {
    },
    setup() {
        const showMenu = ref(false);
        const atTop = ref(true);

        const toggleMenu = () => {
            showMenu.value = !showMenu.value;
        };

        const handleScroll = () => {
            atTop.value = window.scrollY < 50; // 50px from top
        };

        onMounted(() => {
            window.addEventListener('scroll', handleScroll);
            handleScroll(); // set initial value
        });

        onUnmounted(() => {
            window.removeEventListener('scroll', handleScroll);
        });

        return { showMenu, toggleMenu, atTop };
    }
};
</script>
