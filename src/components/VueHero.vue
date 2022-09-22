<template>
    <section class="relative mb-20">
        <div class="container flex flex-col-reverse items-center lg:flex-row gap-12 md:gap-24 mt-14 lg:mt-28" >
            <!-- content -->
            <div class="flex flex-1 flex-col gap-6 z-10">
                <h2 class="text-3xl text-center lg:text-left lg:text-5xl">A Simple Bookmark Manager</h2>
                <p 
                class="text-center text-bookmark-grey lg:text-left text-lg"
                >A clean and simple interface to organize your favourite websites. Open a new browser tab and see your sites load instantly. Try it for free.</p>
                <div class="flex justify-center gap-4 lg:justify-start">
                    <button class="button button-purple">Get in on Chrome</button>
                    <button class="button button-white">Get in on Firefox</button>
                </div>
            </div>

            <!-- image -->
            <div class="flex flex-1 justify-center z-10">
                <img class="w-5/6 h-5/6 md:w-full md:h-full" src="../../public/imgs/hero-bg.png">
            </div>

            <!-- background -->
            <div class="hidden absolute h-80 w-2/5 bg-bookmark-purple right-0 top-32 rounded-l-full md:block"></div>
        </div>
    </section>
    
</template>