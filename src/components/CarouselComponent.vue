<script setup>
import { Carousel } from 'flowbite-vue'

const props = defineProps({
    pictures: {
        type: Array,
        default() {
            return [
                {
                    'src': 'https://img.freepik.com/premium-vector/colorful-welcome-design-template-welcome-letters-banner-welcome-text-design_471203-519.jpg?w=2000',
                    'alt': 'Picture 1',
                },
            ]
        },
    },
})

</script>
<template>
  <Carousel :pictures="pictures" :indicators="false"></Carousel>
</template>
