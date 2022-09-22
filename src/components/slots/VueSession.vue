<script setup>
    // định nghĩa ra props. => nhận vào giá trị nào hiển thị trước cho component. 
    const props = defineProps({ 
        isContentLeft:{
            type:Boolean,
            default:true
        }
    })
    let dimensionFlex = props.isContentLeft === true ? 'lg:flex-row' : 'lg:flex-row-reverse'
</script>

<template>
    <!-- Bookmark  -->
    <div :class='dimensionFlex' class="flex flex-col justify-center lg:items-center gap-12 lg:gap-24 mt-24">
        <div class="flex-1 flex justify-center">
           <slot name='image'></slot>
        </div>
        <div class="flex-1 flex flex-col items-center text-center lg:text-left lg:items-start gap-4">
            <h3 class="text-3xl">
                <slot name='contentTitle' ></slot>
            </h3>
            <p class="text-center lg:text-left w-5/6 lg:w-full">
                <slot name='contentBody'></slot>
            </p>
            <div>
                <button class="button button-purple">
                    <slot name='contentButton'></slot>
                </button>
            </div>
        </div>
    </div>
</template>

