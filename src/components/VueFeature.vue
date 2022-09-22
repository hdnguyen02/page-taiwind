<script setup>
    import VueSession from './slots/VueSession.vue'
</script>
<template>
    <section class="flex flex-col justify-center bg-gray-200 relative pt-24">
        <div class="container">

            <!-- introduce -->
            <div class="text-center w-1/2 mx-auto">
                <h2 class="text-3xl mb-4">Features</h2>
                <p class="text-gray-500">Our aim is to make it quick and easy for you to access your favourite websites. Your bookmarks sync between your devices so you can access them on the go.</p>
            </div>

            <VueSession>
                <template #image>
                    <img class="w-5/6 lg:w-full" src="../../public/imgs/illustration-features-tab-1.png" alt="">
                </template>
                <template #contentTitle> Bookmark in one click </template>
                <template #contentBody>Organize your bookmarks however you like. Our simple drag-and-drop interface gives you complete control over how you manage your favourite sites.</template>
                <template #contentButton>More info</template>
            </VueSession>

            <VueSession is-content-left="false">
                <template #image>
                    <img class="w-5/6 lg:w-full" src="../../public/imgs/illustration-features-tab-2.png" alt="">
                </template>
                <template #contentTitle> Intelligent search </template>
                <template #contentBody>Our powerful search feature will help you find saved sites in no time at all. No need to crawl through all of your bookmarks .</template>
                <template #contentButton>More info</template>
            </VueSession>

            <VueSession>
                <template #image>
                    <img class="w-5/6 lg:w-full" src="../../public/imgs/illustration-features-tab-3.png" alt="">
                </template>
                <template #contentTitle> Share your bookmarks </template>
                <template #contentBody>Our powerful search feature will help you find saved sites in no time at all. No need to crawl through all of your bookmarks .</template>
                <template #contentButton>More info</template>
            </VueSession>
        </div>
    </section>
</template>