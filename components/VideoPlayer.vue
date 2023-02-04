<template>
  <iframe
    width="560"
    :src="`https://player.vimeo.com/video/${props.videoId}`"
    height="315"
    title="Video Player"
    frameborder="0"
    allow="autoplay"
    allowfullscreen
  ></iframe>
</template>
<script lang="ts" setup>
const props = defineProps({
  videoId: {
    type: Number,
    required: true,
  },
});
</script>
<style scoped></style>
