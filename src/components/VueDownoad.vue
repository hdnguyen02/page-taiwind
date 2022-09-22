<script setup>
import ItemDownload from './slots/ItemDownload.vue';
</script>
<template>
    <section>
        <div class="container flex flex-col justify-center mt-24">
            <!-- intro -->
            <div class="text-center">
                <h2 class="text-3xl">Download the extension</h2>
                <p class="mt-4 text-gray-600">We’ve got more browsers in the pipeline. Please do let us know if you’ve
                    got a favourite you’d like us to prioritize.</p>
            </div>

            <!-- column -->
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 mt-12">
                <ItemDownload>
                    <template #img>
                        <img class="w-28 h-28" src="../../public/imgs/logo-chrome.svg" alt="">
                    </template>
                    <template #contentTitle>Add to chrome</template>
                    <template #contentBody>Minimum version 62</template>
                </ItemDownload>

                <ItemDownload>
                    <template #img>
                        <img class="w-28 h-28" src="../../public/imgs/logo-firefox.svg" alt="">
                    </template>
                    <template #contentTitle>Add to Firefox</template>
                    <template #contentBody>Minimum version 62</template>
                </ItemDownload>

                <ItemDownload>
                    <template #img>
                        <img class="w-28 h-28" src="../../public/imgs/logo-opera.svg" alt="">
                    </template>
                    <template #contentTitle>Add to Opera</template>
                    <template #contentBody>Minimum version 62</template>
                </ItemDownload>
            </div>
        </div>
    </section>
</template>