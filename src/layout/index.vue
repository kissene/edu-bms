<template>
  <div class="layout">
    <h1>头部</h1>
    <h1>侧边栏</h1>

    <!-- 子路由出口 -->
    <router-view />
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'LayoutIndex'
})
</script>

<style lang="scss" scoped>

</style>
