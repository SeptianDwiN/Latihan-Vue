<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://ih1.redbubble.net/image.2160024675.2720/poster,840x830,f8f8f8-pad,1000x1000,f8f8f8.jpg',
    'alt': 'Picture 1',
  },
 
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>