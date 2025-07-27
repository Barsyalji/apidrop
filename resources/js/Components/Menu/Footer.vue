<template>
    <div class="airdrop-alert min-h-screen py-12 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="flex border-b border-gray-200">
                <!-- Header Section -->
                <div class=" contaner text-center mb-12 w-1/2">
                    <div class="p-6">
                        <div>
                            <img src="/images\airdrop-alert-logo.avif" alt="" srcset="" class="w-1/4">
                        </div>
                        <p class="text-s text-white max-w-3xl mx-auto">
                            AirdropAlert.com is the cryptocurrency-arranged library to find trusted airdrop campaigns,
                            giveaways and more. Helping millions of people discover new projects & find new ways to
                            earn cryptocurrency since 2017.
                        </p>
                        <div class="flex items-center space-x-4  p-4">
                            <a v-for="(icon, index) in icons" :key="index" :href="icon.url"
                                class="w-10 h-10 flex items-center justify-center border border-white rounded-full text-white hover:text-gray-300 hover:scale-105 transition"
                                target="_blank">
                                <i :class="icon.class"></i>
                            </a>
                        </div>

                    </div>
                </div>

                <!-- Links Sections -->
                <div class=" contaner grid grid-cols-1 md:grid-cols-3 gap-8 mb-12 w-1/2">
                    <!-- Company Links -->
                    <div class="text-white p-6 rounded-lg shadow-sm">
                        <h2 class=" pb-2">Company</h2>
                        <ul class="space-y-0">
                            <li v-for="link in companyLinks" :key="link.text">
                                <a :href="link.href" class="text-white hover:text-blue-600 transition-colors">
                                    {{ link.text }}
                                </a>
                            </li>
                        </ul>
                    </div>
                    <!-- Useful Links -->
                    <div class=" p-6 text-white">
                        <h2 class="">Useful links</h2>
                        <ul class="space-y-0">
                            <li v-for="link in usefulLinks" :key="link.text">
                                <a :href="link.href" class="text-white hover:text-blue-600 transition-colors">
                                    {{ link.text }}
                                </a>
                            </li>
                        </ul>
                    </div>
                    <!-- List Airdrop Links -->
                    <div class="p-6 rounded-lg text-white">
                        <ul class="grid grid-row-1 gap-4 w-full">
                            <li v-for="link in listAirdropLinks" :key="link.text" class="flex-1">
                                <a :href="link.href"
                                    class="border border-cyan-400 w-full text-cyan-400 px-6 py-2 rounded-full font-semibold hover:bg-cyan-400 hover:text-black transition text-center block">
                                    {{ link.text }}
                                </a>
                            </li>
                        </ul>
                    </div>

                </div>
            </div>

            <!-- Disclaimer Section -->
            <div class=" p-6 rounded-lg shadow-sm mb-4">
                <p class="text-white">
                  Disclaimer: The information provided on this website is for informational purposes only and does not,
                    under any circumstances, constitute investment advice, financial advice, trading advice,
                    or any other form of advice. Arrangable/capacity decisions may recommendation or endorsement
                    for its purchase, sale, or retention of any cryptocurrency by any visitor or user of this
                    website. Prior to making any investment decisions, it is imperative that individuals conduct
                    thorough due diligence and seek consultation with a qualified financial adviser.
                </p>
            </div>
            <!-- Footer -->
            <div class="text-center text-gray-500 text-sm">
                <p>© AirdropAlert.com 2025 – All rights reserved</p>
            </div>
        </div>
    </div>
</template>

<script>
    import '@fortawesome/fontawesome-free/css/all.min.css'
export default {

    name: 'AirdropAlert',
    data() {
        return {
            companyLinks: [
                { text: 'About Us', href: '#' },
                { text: 'General Terms', href: '#' },
                { text: 'Privacy Policy', href: '#' },
                { text: 'Disclaimer', href: '#' },
                { text: 'Contact', href: '#' }
            ],
            usefulLinks: [
                { text: 'Browse Airdrops', href: '#' },
                { text: 'Search Projects', href: '#' },
                { text: 'Exchanges', href: '#' },
                { text: 'Stay Safe', href: '#' },
                { text: 'FAQs', href: '#' },
                { text: 'RSS Feed', href: '#' }
            ],
            listAirdropLinks: [
                { text: 'List Airdrop', href: '#' },
                { text: 'Advertise', href: '#' },
                { text: 'Partnerships', href: '#' }
            ],
            icons: [
                { class: 'fab fa-tiktok', url: '#' },
                { class: 'fab fa-x-twitter', url: '#' }, // X (Twitter)
                { class: 'fab fa-facebook-f', url: '#' },
                { class: 'fab fa-instagram', url: '#' },
                { class: 'fab fa-youtube', url: '#' },
                { class: 'fab fa-linkedin-in', url: '#' }
            ]
        }
    }
}
</script>

<style scoped>
/* You can add custom styles here if needed */
.airdrop-alert {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}
</style>
