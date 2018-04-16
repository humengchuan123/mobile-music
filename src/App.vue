<template>
  <div id="app">
    <div class="header">
      <v-header></v-header>
      <tab></tab>
      <keep-alive>
      <router-view></router-view>
    </keep-alive>
    </div>
  </div>
</template>

<script>
import header from './components/header/header'
import tab from './components/tab/tab'
export default {
  components:{
    "v-header":header,
      tab

  }
}
</script>

<style>
</style>
