<template>
    <div class="header">
        <Controlbar />
        <Menu />
        <SearchBar />
        <Profile />
    </div>
</template>

<script lang="ts">
import { defineComponent } from "@vue/runtime-core";
import Controlbar from "./controlbar/controlbar.vue";
import Menu from "./menu/menu.vue";
import SearchBar from "./searchBar/searchBar.vue";
import Profile from "./profile/profile.vue";

export default defineComponent({
    components:{
        Controlbar,
        Menu,
        SearchBar,
        Profile
    }
})
</script> 

<style scoped>
    .header{
        display: flex;
        align-items: center;
    }
</style>