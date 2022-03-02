<template>
    <div class="header-menu">
        <router-link to="/" active-class="active">音乐</router-link>
        <router-link to="/" active-class="active">MV</router-link>
        <router-link to="/" active-class="active">电台</router-link>
        <router-link to="/" active-class="active">歌房</router-link>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .header-menu a{
        padding: 20px 30px;
        text-decoration: none;
        color: var(--inactive-color);
        border-bottom: 2px solid transparent;
        transition: 0.3s;
        white-space: nowrap;
    }
    .active,.header-menu a:hover{
        color: var(--theme-color);
        border-bottom: 2px solid var(--theme-color);
    }

    .header>.header-menu{
        display: flex;
        align-items:center;
    }
</style>