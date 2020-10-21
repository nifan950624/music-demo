<template>
  <div id="app">
    <TopNav />
    <router-view />
  </div>
</template>
<script lang="ts">
import HelloWorld from '@/components/HelloWorld.vue'
import TopNav from '@/components/Nav/index.vue'
import { Component, Vue } from 'vue-property-decorator'

@Component({ components: { TopNav } })
export default class App extends Vue {}
</script>

<style>
</style>
