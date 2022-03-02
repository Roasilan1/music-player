<template>
  <Background />
  <Main />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Background from "@/components/background/Background.vue";
import Main from "@/components/main/main.vue";

@Options({
  components: {
    Background,
    Main
  },
})
export default class App extends Vue {}
</script>

<style lang="css">
@import url("./assets/css/main.css");
</style>
