<template>
  <view class="content"> </view>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'

@Component
export default class App extends Vue {
  mpType = 'app'

  onLaunch(): void {
    console.log('App Launch')
  }

  onShow(): void {
    console.log('App Show')
  }

  onHide(): void {
    console.log('App Hide')
  }
}
</script>

<style>
/*每个页面公共css */
</style>
