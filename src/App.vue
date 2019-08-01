<template>
  <div id="app" class="flex-column" style="height:100%;width:100%">
    <Header></Header>
    <div class="flex flex1" style="width:100%">
      <Aside></Aside>
      <router-view class="flex1"></router-view>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Aside from '@/components/Aside.vue'

export default {
  name: 'app',
  components: {
    Header,
    Aside
  }
}
</script>

<style>
</style>
