<template>
    <!-- Main Content -->
    <div class="container mx-auto px-4 w-10/12 pb-10">
        <div class=" pt-5 text-white flex flex-col">
            <div class="flex flex-col md:flex-row items-center justify-between flex-1 px-6 md:px-12 mt-2 md:mt-4">
                <!-- Left -->
                <div class="max-w-xl py-1 md:py-1 text-center md:text-left md:w-1/2">

                    <h3 class="text-4xl sm:text-5xl font-bold mb-6 leading-tight w-full">
                        Bringing you new<br>
                        airdrops <span class="text-cyan-400">every day</span><br>
                        since 2017
                    </h3>
                    <p>AirdropAlert is the most trusted place in web3 to find the latest airdrop campaigns. Discover new
                        crypto airdrops and learn how to join them with easy-to-follow guides.</p>
                    <br>
                    <div class="flex flex-wrap justify-center md:justify-start gap-4 mb-8 w-full">
                        <button
                            class="bg-cyan-400 text-black px-6 py-2 rounded-full font-semibold hover:bg-cyan-500 transition">
                            view All Airdrops
                        </button>
                        <button
                            class="border border-cyan-400 text-cyan-400 px-6 py-2 rounded-full font-semibold hover:bg-cyan-400 hover:text-black transition">
                            List Airdrops
                        </button>
                    </div>
                </div>

                <!-- Right (Phone Image) -->
                <div class="relative flex-1 flex py-1 md:py-1 justify-center items-center mt-10 md:mt-0 md:w-1/2">
                    <!-- First image (on top) -->
                    <img src="/images/AirdropAlert-app-1.avif" alt="Phone" class="drop-shadow-2xl relative z-10" />
                    <!-- Second image (behind and offset) -->
                    <img src="/images/AirdropAlert-app2.avif" alt="Phone"
                        class="drop-shadow-2xl absolute top-5 right-5 z-0"
                        style="margin-right: 20px; margin-top: 20px;" />
                </div>

            </div>
            <div class=" md:flex-row items-center justify-between flex-1 px-6 md:px-12 mt-4 md:mt-16">

                <div class="text-cyan-400 text-base font-semibold mb-6">
                    TRUSTED BY WELL-KNOWN CRYPTO BRANDS
                </div>
                <div class="flex flex-wrap gap-5 md:gap-5 justify-center md:justify-start w-full">
                    <!-- Card 1 -->
                    <div
                        class="bg-white bg-opacity-5 hover:bg-[rgba(44,212,217,0.1)] transition-colors duration-300 border border-gray-700 rounded-lg px-8 py-6 flex items-center min-w-[180px] min-h-[80px]">
                        <img src="/images/airdropalert-bybit-logo.avif" alt="Bybit Logo" class="h-8" />
                    </div>

                    <!-- Card 2 -->
                    <div
                        class="bg-white bg-opacity-5 hover:bg-[rgba(44,212,217,0.1)] transition-colors duration-300 border border-gray-700 rounded-lg px-8 py-6 flex items-center min-w-[180px] min-h-[80px]">
                        <img src="/images/cex-logo-airdropalert-1.avif" alt="Kelp" class="h-8 mr-3" />
                    </div>

                    <!-- Card 3 -->
                    <div
                        class="bg-white bg-opacity-5 hover:bg-[rgba(44,212,217,0.1)] transition-colors duration-300 border border-gray-700 rounded-lg px-8 py-6 flex items-center min-w-[180px] min-h-[80px]">
                        <img src="/images/kelp-dao-logo.avif" alt="SwissBorg" class="h-8 mr-3" />
                    </div>

                    <!-- Card 4 -->
                    <div
                        class="bg-white bg-opacity-5 hover:bg-[rgba(44,212,217,0.1)] transition-colors duration-300 border border-gray-700 rounded-lg px-8 py-6 flex items-center min-w-[180px] min-h-[80px]">
                        <img src="/images/Nexo-white.avif" alt="NEXO" class="h-8 mr-3" />
                    </div>

                    <!-- Card 5 -->
                    <div
                        class="bg-white bg-opacity-5 hover:bg-[rgba(44,212,217,0.1)] transition-colors duration-300 border border-gray-700 rounded-lg px-8 py-6 flex items-center min-w-[180px] min-h-[80px]">
                        <img src="/images/swissborg.avif" alt="CEX.IO" class="h-8 mr-3" />
                    </div>
                </div>

            </div>
            <!-- Browse Airdrops Section -->
            <div class="md:flex-row items-center justify-between flex-1 px-6 md:px-12 mt-2 md:mt-16">
                <h2 class="text-center text-2xl md:text-2xl text-white mb-8">
                    Browse airdrops effortlessly with easy search & filter options
                </h2>

               <div class="flex flex-col md:flex-row gap-6 justify-center">
    <!-- Featured Airdrops Card -->
    <div style="background-image: url('/images/Why-airdropalert1-1.avif');"
        class="bg-cover bg-center rounded-xl p-6 flex-1 min-w-[260px] max-w-xs mx-auto transition duration-300 hover:opacity-90">
        <div class="flex flex-col items-center p-6">
            <div class="mb-4">
                <img src="/images/Airdrop-alert.avif" alt="" class="py-8">
            </div>
            <div class="flex flex-col items-center pb-4">
                <h3 class="text-cyan-400 font-bold text-lg mb-2">Featured Airdrops</h3>
                <p class="text-gray-300 text-sm text-center mb-2">Discover hand-picked, quality airdrops updated daily.</p>
            </div>
        </div>
    </div>

    <!-- DeFi Airdrops Card -->
    <div style="background-image: url('/images/Why-airdropalert2.avif');"
        class="bg-cover bg-center rounded-xl p-6 flex-1 min-w-[260px] max-w-xs mx-auto transition duration-300 hover:opacity-90">
        <div class="flex flex-col items-center p-6">
            <div class="mb-4">
                <img src="/images/Airdrop-alert.avif" alt="" class="py-8">
            </div>
            <div class="flex flex-col items-center pb-4">
                <h3 class="text-cyan-400 font-bold text-lg mb-2">DeFi Airdrops</h3>
                <p class="text-gray-300 text-sm text-center mb-2">Explore the latest DeFi project airdrops and maximize your rewards.</p>
            </div>
        </div>
    </div>

    <!-- Solana Airdrops Card -->
    <div style="background-image: url('/images/Why-airdropalert3.avif');"
        class="bg-cover bg-center rounded-xl p-6 flex-1 min-w-[260px] max-w-xs mx-auto transition duration-300 hover:opacity-90">
        <div class="flex flex-col items-center p-6">
            <div class="mb-4">
                <img src="/images/Airdrop-alert.avif" alt="" class="py-8">
            </div>
            <div class="flex flex-col items-center pb-4">
                <h3 class="text-cyan-400 font-bold text-lg mb-2">Solana Airdrops</h3>
                <p class="text-gray-300 text-sm text-center mb-2">Explore exclusive Solana ecosystem airdrops and opportunities.</p>
            </div>
        </div>
    </div>
</div>


                <div class="flex justify-center mt-8">
                    <div class=" border-b border-cyan-400">
                        <button class="text-white text-basc px-6  hover:text-cyan-300 transition">
                            Discover all airdrops
                        </button>
                    </div>
                </div>
            </div>

            <!-- How It Works Section -->
            <div class=" md:flex-row items-center justify-between flex-1 px-6 md:px-12 mt-2 md:mt-16 ">
                <h4 class="text-sm mb-2 bg-gradient-to-br from-[#0693e3] to-[#9b51e0] bg-clip-text text-transparent">
                    Get started
                </h4>
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-12">How it works</h2>
                <div class="flax flex-col md:flex-row gap-12">
                    <div class="flex flex-col md:flex-col gap-12">
                        <!-- For Airdrop Farmers -->
                        <!-- For Airdrop Farmers -->
                        <div class="flex flex-row gap-4 border-b border-gray-700 pb-12">
                            <!-- Left Column -->
                            <div class="flex flex-col gap-4 w-full md:w-1/3">
                                <div class="text-white text-1xl mb-2">For Airdrop farmers</div>
                                <button
                                    class="w-1/2 border border-cyan-400 text-cyan-400 px-4 py-2 rounded-full font-semibold mb-6 hover:bg-cyan-400 hover:text-black transition">
                                    Join Airdrops
                                </button>
                            </div>

                            <!-- Right Column -->
                            <div class="flex flex-row gap-12 w-full md:w-2/3">
                                <div class="flex items-start gap-4">
                                    <div class="text-cyan-400 font-bold text-lg">01.</div>
                                    <div>
                                        <div class="text-cyan-400 font-semibold text-sm mb-1">BROWSE AIRDROPS</div>
                                        <div class="text-gray-300 text-xs">
                                            Use advanced filters to easily search through airdrop opportunities and
                                            find ones that match your interests and which blockchain you prefer to
                                            farm on.
                                        </div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-4">
                                    <div class="text-cyan-400 font-bold text-lg">02.</div>
                                    <div>
                                        <div class="text-cyan-400 font-semibold text-sm mb-1">SELECT AND PARTICIPATE
                                        </div>
                                        <div class="text-gray-300 text-xs">
                                            Choose an airdrop campaign on your preferred blockchain, follow the
                                            step-by-step guide provided, and start participating right away.
                                        </div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-4">
                                    <div class="text-cyan-400 font-bold text-lg">03.</div>
                                    <div>
                                        <div class="text-cyan-400 font-semibold text-sm mb-1">STAY UPDATED</div>
                                        <div class="text-gray-300 text-xs">
                                            Enable notifications to receive real-time alerts about the latest
                                            airdrops, TGE, and eligibility checks, ensuring you never miss out on
                                            free crypto tokens.
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- For Campaign Managers -->
                        <div class="flex flex-row gap-4 pb-12">
                            <!-- Left Column -->
                            <div class="flex flex-col gap-4 w-full md:w-1/3">
                                <div class="text-white text-1xl mb-2">For Campaign managers</div>
                                <button
                                    class="border w-1/2 border-cyan-400 text-cyan-400 px-4 py-2 rounded-full font-semibold mb-6 hover:bg-cyan-400 hover:text-black transition">
                                    Airdrop Promotion
                                </button>
                            </div>

                            <!-- Right Column -->
                            <div class="flex flex-row gap-12 w-full md:w-2/3">
                                <div class="flex items-start gap-4">
                                    <div class="text-cyan-400 font-bold text-lg">01.</div>
                                    <div>
                                        <div class="text-cyan-400 font-semibold text-sm mb-1">LIST YOUR AIRDROP</div>
                                        <div class="text-gray-300 text-xs">
                                            Go to the List Airdrop page, select the appropriate package that suits
                                            your needs and get your campaign rolling.
                                        </div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-4">
                                    <div class="text-cyan-400 font-bold text-lg">02.</div>
                                    <div>
                                        <div class="text-cyan-400 font-semibold text-sm mb-1">SUBMIT FOR REVIEW</div>
                                        <div class="text-gray-300 text-xs">
                                            Complete the form with your airdrop details and submit it for our review
                                            to ensure compliance and approval.
                                        </div>
                                    </div>
                                </div>
                                <div class="flex items-start gap-4">
                                    <div class="text-cyan-400 font-bold text-lg">03.</div>
                                    <div>
                                        <div class="text-cyan-400 font-semibold text-sm mb-1">BOOST YOUR CAMPAIGN</div>
                                        <div class="text-gray-300 text-xs">
                                            Choose from a variety of add-ons to increase your airdrop’s visibility
                                            and engagement, and keep your users updated throughout the campaign.
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
            <!-- Stats & Testimonials Section -->
            <!-- Stats -->
            <div class="flex flex-col md:flex-row items-center justify-center text-center px-6 md:px-12 mt-16 gap-10">

                <!-- Left Section: Stats -->
                <div class="text-center">
                    <div class="text-white text-3xl mb-4 pb-4">
                        AirdropAlert users claimed <span class="text-cyan-400 font-semibold">millions of
                            dollars</span> in value
                    </div>
                    <div class="flex justify-center gap-64 mt-4">
                        <div>
                            <div class="text-8xl font-bold text-white">5K+</div>
                            <div class="text-cyan-400 text-xs mt-1">AIRDROPS LISTED</div>
                        </div>
                        <div>
                            <div class="text-8xl font-bold text-white">180</div>
                            <div class="text-cyan-400 text-xs mt-1">COUNTRIES</div>
                        </div>
                        <div>
                            <div class="text-8xl font-bold text-white">15</div>
                            <div class="text-cyan-400 text-xs mt-1">SUPPORTED LANGUAGES</div>
                        </div>
                    </div>
                </div>

            </div>
            <!-- Testimonials -->
            <div class="flex flex-col md:flex-row justify-between items-start gap-12 w-full mt-16">
                <div class=" w-full md:w-1/3">
                    <div class="text-cyan-400 text-1xl mb-2">Wall of Fame</div>
                    <h2 class="text-white text-4xl font-bold mb-2">Words from our users</h2>
                    <p class="text-white text-base break-words-1xl">
                        Over the last eight years, we have immersed ourselves in the world of airdrops, and we
                        know that the quest for reliable information can be daunting. That’s why we’ve created
                        our user-friendly airdrop guides to make your farming journey smoother and more
                        enjoyable. Our focus is safety and user experience. But don’t just take our word for
                        it—discover what our users have to share.
                    </p>
                </div>
                <div class="flex flex-wrap gap-8 justify-center w-full md:w-2/3">
                    <!-- Card 1 -->
                    <div
                        class="bg-[rgba(44,212,217,0.25)] hover:bg-[rgba(44,212,217,0.50)]  p-4 transition-colors duration-300 border border-gray-700 rounded-xl p-6 flex-1 min-w-[260px] max-w-xs">
                        <div class="p-4">
                            <p class="text-gray-200 text-sm mb-4">
                                "Big kudos to the team for consistently providing such a high-quality resource. What I
                                love most is how they've adapted and grown alongside the crypto industry. From the
                                simple days of straightforward airdrops to now integrating DeFi, NFTs, and community
                                incentives, they've stayed ahead of the curve!"
                            </p>
                            <div class="flex items-center gap-3 p-4 mt-4">
                                <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Didi"
                                    class="w-8 h-8 rounded-full border border-cyan-400" />
                                <div>
                                    <div class="text-cyan-400 text-sm font-semibold">Didi Taihuttu</div>
                                    <div class="text-white text-sm">@Diditaihuttu | The Bitcoin Family</div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Card 2 -->
                    <div
                        class="bg-[rgba(44,212,217,0.25)] hover:bg-[rgba(44,212,217,0.50)]  p-4 transition-colors duration-300 border border-gray-700 rounded-xl p-6 flex-1 min-w-[260px] max-w-xs">
                        <div class="p-4">
                            <p class="text-gray-200 text-sm mb-4">
                                "There are a lot of scams out there in the world of cryptocurrencies, especially when it
                                comes to farming airdrops. AirdropAlert has been a reliable source for safe and legit
                                airdrop campaigns for me and I can't thank them enough for all their hard work. Received
                                plenty of NFT and Ordinal airdrops thanks to them!"
                            </p>
                            <div class="flex items-center gap-3 p-4 mt-4">
                                <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="L3yum"
                                    class="w-8 h-8 rounded-full border border-cyan-400" />
                                <div>
                                    <div class="text-cyan-400  text-sm font-semibold">L3yum</div>
                                    <div class="text-white  text-sm">@L3yum | NFT & Ordinal Farmer</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div
                        class="bg-[rgba(44,212,217,0.25)] hover:bg-[rgba(44,212,217,0.50)]  p-4 transition-colors duration-300 border border-gray-700 rounded-xl p-6 flex-1 min-w-[260px] max-w-xs">
                        <div class="p-4">

                            <p class="text-gray-200 text-sm mb-4">
                                "I remember when claiming airdrops was as simple as a Telegram tap. Nowadays there is
                                more to it. Thanks to AirdropAlert I was eligible for a ton of staking airdrops and
                                earlier this year I plotted to meme coins through the guides they provided."
                            </p>
                            <div class="flex items-center gap-3 p-4 mt-4">
                                <img src="https://randomuser.me/api/portraits/men/65.jpg" alt="RollingRut"
                                    class="w-8 h-8 rounded-full border border-cyan-400" />
                                <div>
                                    <div class="text-cyan-400  text-sm font-semibold">RollingRut</div>
                                    <div class="text-white  text-sm">@CryptoRut | Meme Coin Farmer</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 4 -->
                    <div
                        class="bg-[rgba(44,212,217,0.25)] hover:bg-[rgba(44,212,217,0.50)]  p-4 transition-colors duration-300 border border-gray-700 rounded-xl p-6 flex-1 min-w-[260px] max-w-xs">
                        <div class="p-4">
                            <p class="text-gray-200 text-sm mb-4">
                                "AirdropAlert helped me cook up a great Blast airdrop. It's my go-to place to search for
                                new trends in airdrops. If you can't find a new cook by yourself, search their DeFi
                                pages. In short, best team, easy airdrop guides, and good content. All you need."
                            </p>
                            <div class="flex items-center gap-3 p-4 mt-4">
                                <img src="https://randomuser.me/api/portraits/men/77.jpg" alt="Fancy"
                                    class="w-8 h-8 rounded-full border border-cyan-400" />
                                <div>
                                    <div class="text-cyan-400  text-sm font-semibold">Fancy</div>
                                    <div class="text-white  text-sm">@FancyXBT | Trader & Web3 Chef</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

            <!-- Why use AirdropAlert Section -->
            <div class="mt-20 px-6 md:px-12">
                <div class="text-center mb-4">
                    <span class="text-sm text-cyan-400 font-semibold">Benefits of <span
                            class="text-white">AirdropAlert</span></span>
                </div>
                <h2 class="text-3xl md:text-4xl font-bold text-white text-center mb-12">Why use AirdropAlert?</h2>
                <div class="flex flex-col md:flex-row gap-8 justify-center">
                    <!-- Card 1 -->
                    <div
                        class="group bg-white bg-opacity-5 border border-gray-700 rounded-xl p-8 flex-1 min-w-[260px] max-w-sm mx-auto flex flex-col items-start transition-shadow hover:shadow-2xl hover:shadow-cyan-400/30">
                        <div class="w-15 h-15 bg-cyan-500 overflow-hidden rounded-md mb-4">
                            <img src="/images/verified-airdrops.avif" alt="Verified Airdrops"
                                class="w-full h-full p-1 object-cover" />
                        </div>
                        <h3 class="text-white font-bold text-lg mb-2">Most trusted library</h3>
                        <p class="text-gray-300 text-sm">
                            Join over millions of satisfied airdrop hunters who rely on our real-time crypto airdrop
                            alerts and user-friendly interface to stay updated. AirdropAlert was the first ever
                            airdrop aggregator and is still recognized as the most trusted library for finding safe
                            crypto airdrops across web3. We’re the home of airdrop farmers.
                        </p>
                    </div>

                    <!-- Card 2 -->
                    <div
                        class="group bg-white bg-opacity-5 border border-gray-700 rounded-xl p-8 flex-1 min-w-[260px] max-w-sm mx-auto flex flex-col items-start transition-shadow hover:shadow-2xl hover:shadow-cyan-400/30">
                        <div class="w-15 h-15 bg-cyan-500 overflow-hidden rounded-md mb-4">
                            <img src="/images/airdropalert-app-icon-1.avif" alt="App Icon"
                                class="w-full h-full object-cover p-1" />
                        </div>
                        <h3 class="text-white font-bold text-lg mb-2">The latest airdrops at your fingertips</h3>
                        <p class="text-gray-300 text-sm">
                            Download the AirdropAlert mobile app (coming soon) to instantly access the latest
                            cryptocurrency airdrops, play-to-earn games, trading competitions and giveaways on the
                            go. The world of airdrops at your fingertips, any time, any blockchain or layer 2, any
                            place.
                        </p>
                    </div>

                    <!-- Card 3 -->
                    <div
                        class="group bg-white bg-opacity-5 border border-gray-700 rounded-xl p-8 flex-1 min-w-[260px] max-w-sm mx-auto flex flex-col items-start transition-shadow hover:shadow-2xl hover:shadow-cyan-400/30">
                        <div class="w-15 h-15 bg-cyan-500 overflow-hidden rounded-md mb-4">
                            <img src="/images/library-airdrop-icon-1.avif" alt="Library Icon"
                                class="w-full h-full object-cover p-1" />
                        </div>
                        <h3 class="text-white font-bold text-lg mb-2">More than just airdrops</h3>
                        <p class="text-gray-300 text-sm">
                            AirdropAlert is more than just a library of free airdrops. Dive into in-depth blogs,
                            meme coins, NFTs, trading analysis, step-by-step guides and the latest updates from the
                            crypto industry. Stay informed and ahead of the curve with our expertly curated content.
                            Evolve yourself from airdrop farmer to an all-round crypto bro.
                        </p>
                    </div>
                </div>

            </div>

            <!-- Trending Cryptocurrency Topics Section -->
            <div class="flex flex-col md:flex-row items-center justify-between flex-1 px-6 md:px-12 mt-20 gap-12">
                <!-- Left: Text Content -->
                <div class="max-w-lg">
                    <div class="mb-2">
                        <span class="text-sm font-semibold" style="color: #b366ff;">Trending</span>
                        <span class="text-white text-sm ml-1">cryptocurrency topics</span>
                    </div>
                    <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">More than just airdrops</h2>
                    <p class="text-white text-sm mb-6">
                        AirdropAlert offers a wealth of content that goes beyond just cryptocurrency airdrops.
                        Find a wide range of topics, including the latest trends in meme coins, insightful trading
                        blogs, crypto news and the fascinating world of NFTs. Dive into our articles to explore
                        these exciting subjects and stay ahead in the ever-evolving crypto landscape.
                    </p>
                    <a href="/blog">
                        <button
                            class="bg-cyan-400 text-black px-6 py-2 rounded-full font-semibold hover:bg-cyan-500 transition">
                            Go to the blog
                        </button>
                    </a>
                </div>
                <!-- Right: Blog Preview Image -->
                <div class="w-full md:w-[600px] flex justify-center">
                    <img src="/images\AirdropAlert-blogs.avif" alt="AirdropAlert Blog Preview"
                        class="rounded-xl   w-full max-w-[600px]" />
                </div>
            </div>

            <!-- Beginner Friendly Section -->
            <div class=" py-14 px-6 md:px-16 mt-20 mb-10 pt-16">
                <div class="text-center mb-12">
                    <span class="text-sm font-semibold" style="color: #b366ff;">Beginner</span>
                    <span class="text-sm font-semibold text-cyan-400 ml-1">Friendly</span>
                    <h2 class="text-3xl md:text-4xl font-bold text-white mt-2 mb-4">
                        New to crypto and farming airdrops?
                    </h2>
                </div>
                <div class="flex flex-col md:flex-row gap-10 justify-center">
                    <!-- Stay Safe -->
                    <div class="flex-1 min-w-[220px] max-w-xs mx-auto text-center md:text-left">
                        <div class="text-white font-bold mb-2">Stay safe</div>
                        <div class="text-white text-sm mb-4">
                            It's important that you learn the basics of navigating in crypto and keep your crypto
                            coins safe.
                        </div>
                        <button
                            class="border border-cyan-400 text-cyan-400 px-5 py-2 rounded-full font-semibold hover:bg-cyan-400 hover:text-black transition">
                            Secure your crypto
                        </button>
                    </div>
                    <!-- FAQs -->
                    <div class="flex-1 min-w-[220px] max-w-xs mx-auto text-center md:text-left">
                        <div class="text-white font-bold mb-2">FAQs</div>
                        <div class="text-white text-sm mb-4">
                            Have questions? We're here to help. Explore our frequently asked questions for the
                            answers you need.
                        </div>
                        <button
                            class="border border-cyan-400 text-cyan-400 px-5 py-2 rounded-full font-semibold hover:bg-cyan-400 hover:text-black transition">
                            Explore FAQs
                        </button>
                    </div>
                    <!-- Newsletter -->
                    <div class="flex-1 min-w-[220px] max-w-xs mx-auto text-center md:text-left">
                        <div class="text-white font-bold mb-2">Newsletter</div>
                        <div class="text-white text-sm mb-4">
                            Get the freshest updates on giveaways, airdrops, cryptocurrency news, and airdrop claims
                            delivered directly to your inbox.
                        </div>
                        <button
                            class="border border-cyan-400 text-cyan-400 px-5 py-2 rounded-full font-semibold hover:bg-cyan-400 hover:text-black transition">
                            Subscribe
                        </button>
                    </div>
                    <!-- Guides -->
                    <div class="flex-1 min-w-[220px] max-w-xs mx-auto text-center md:text-left">
                        <div class="text-white font-bold mb-2">Guides</div>
                        <div class="text-white text-sm mb-4">
                            Become a cryptocurrency expert with our in-depth guides and stay updated on industry
                            news.
                        </div>
                        <button
                            class="border border-cyan-400 text-cyan-400 px-5 py-2 rounded-full font-semibold hover:bg-cyan-400 hover:text-black transition">
                            Become an expert
                        </button>
                    </div>
                </div>
            </div>

            <div style="background-image: url('/images/CTA-background-airdropalert1.avif');"
                class=" from-blue-600 to-indigo-700 py-16 px-4 sm:px-6 lg:px-8 text-white">
                <div class="max-w-4xl mx-auto text-center">
                    <h2 class="text-3xl sm:text-4xl font-bold mb-4 leading-tight">
                        Never miss new airdrops<br>
                        <span class="">ever again!</span>
                    </h2>

                    <p class="text-xl sm:text-2xl mb-8 opacity-90">
                        Stay updated with the latest cryptocurrency airdrops and maximize your earnings
                    </p>

                    <button
                        class="bg-cyan-400 hover:bg-cyan-300 text-gray-900 font-bold py-3 px-8 rounded-full text-lg transition-all duration-300 hover:scale-105 shadow-lg hover:shadow-xl">
                        Farm airdrops today
                    </button>

                    <div class="mt-8 flex justify-center space-x-6">
                        <div class="flex items-center">
                            <svg class="w-5 h-5 mr-2 " fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd"
                                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                                    clip-rule="evenodd"></path>
                            </svg>
                            <span>Real-time alerts</span>
                        </div>
                        <div class="flex items-center">
                            <svg class="w-5 h-5 mr-2 " fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd"
                                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                                    clip-rule="evenodd"></path>
                            </svg>
                            <span>Verified projects</span>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
import { ref, onMounted, onUnmounted } from 'vue';
import GuestLayout from '@/Layouts/GuestLayout.vue';

export default {
    name: "Index",
    layout: GuestLayout,
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
