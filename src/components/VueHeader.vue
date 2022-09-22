<template>
    <header>
        <nav class="container flex items-center justify-between py-4 mt-4 sm:mt-12">
            <div><img src="../../public/imgs/logo-bookmark.svg" alt=""></div>
            <ul class="hidden sm:flex sm:gap-12 text-xs text-bookmark-blue">
                <li class="flex items-center"><a href="#">FEATURES</a></li>
                <li class="flex items-center"><a href="#">PRICING</a></li>
                <li class="flex items-center"><a href="#">CONTACT</a></li>
                <li>
                    <button class="block bg-bookmark-red text-bookmark-white px-7 h-10 rounded-lg">
                        LOGIN
                    </button>
                </li>
            </ul>
            <div class="flex sm:hidden">
                <i class="text-2xl fa-solid fa-bars"></i>
            </div>
        </nav>
    </header>
</template>