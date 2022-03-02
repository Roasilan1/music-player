<template>
      <div class="video-bg">
        <video width="320" height="240" autoplay loop muted>
         <source src="https://assets.codepen.io/3364143/7btrrd.mp4" type="video/mp4">
       Your browser does not support the video tag.
       </video>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "@vue/runtime-core";
export default defineComponent({

})
</script>

<style scoped>
    .video-bg{
      position: fixed;
      right: 0;
      top: 0;
      width: 100%;
      height: 100%;
    }
    .video-bg video {
        width: 100%;
        height: 100%;
        -o-object-fit: cover;
        object-fit: cover;
    }
</style>