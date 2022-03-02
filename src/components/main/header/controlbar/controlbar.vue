<template>
    <ul class="header-controlbar">
        <li @click="back"><img src="../../images/返回.png" alt=""></li>
        <li @click="forward"><img src="../../images/返回2.png" alt=""></li>
        <li @click="ref"><img src="../../images/刷新.png" alt=""></li>
    </ul>
</template>

<script>
export default {

}
</script>

<style scoped>
    .header>.header-controlbar{
        display: flex;
        margin: 0;
        align-items: center;
        border-bottom: 1px solid var(--border-color);
        height: 58px;
        flex-shrink: 0;
        margin-right: 105px;
    }
    .header>.header-controlbar>li{
        margin: 0 8px;
    }
</style>