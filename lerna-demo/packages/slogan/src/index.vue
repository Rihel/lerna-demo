<template>
  <div id="app">
    我是一个区块，依赖list-view组件
    <list-view></list-view>
  </div>
</template>

<script>
import listView from 'list-view'

console.log(listView)

export default {
  name: 'app',
  components: {
    [listView.name]: listView
  }
}
</script>

<style>
</style>
