<template>
    <div class="main">
        <Top></Top>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from "@vue/runtime-core";
    import Top from "./header/header.vue";
    export default defineComponent({
        components:{
            Top
        }
    })
</script>

<style scoped>

    .main{
        display: flex;
        flex-grow: 1;
        overflow: hidden;
        background: var(--theme-bg-color);
        position: absolute;
        backdrop-filter: blur(20px);
        border-radius: 14px;
    }
    .slide-left{
        
    }

</style>