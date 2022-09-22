<template>
    <div class="flex flex-col items-center gap-12 shadow-md py-8 rounded-md">
        <div class="flex flex-col items-center gap-4">
            <slot name='img'></slot>
            <h3 class="text-xl">
                <slot name='contentTitle'></slot>
            </h3>
            <p class="text-gray-500">
                <slot name='contentBody'></slot>
            </p>
        </div>
        <div class="w-full px-8">
            <button class="block w-full button button-purple">
                Add & install extension
            </button>
        </div>
    </div>
</template>