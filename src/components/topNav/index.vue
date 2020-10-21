<template>
  <div id="nav">
    <router-link to="/">首页</router-link>
    <router-link to="/about">探索</router-link>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

export default class topNav extends Vue {}
</script>

<style lang="scss" scoped>
.nav {
  display: flex;
}
</style>
