<template>
    <ElContainer class="app-container">
        <ElMain class="main-content">
            <RouterView class="router-view" />
        </ElMain>
    </ElContainer>
</template>

<script setup lang="ts">

</script>

<style>
.app-container {
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    width: 100vw; /* 修改为视口宽度 */
    height: 100vh; /* 修改为视口高度 */
    margin: 0;
}

.main-content {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.router-view {
    display: flex;
    height: 100%;
    width: 100%;
    /* 添加其他必要的样式 */
}
</style>
