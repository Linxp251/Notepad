<template>

  <!-- 主体区域 -->
  <section id="app">
    <DoHeader></DoHeader>
    <DoMain :list="list"></DoMain>
    <DoFooter></DoFooter>
  </section>
</template>

<script>
import DoHeader from './components/DoHeader.vue';
import DoMain from './components/DoMain.vue';
import DoFooter from './components/DoFooter.vue';
export default {
  components:{
    DoHeader,
    DoMain,
    DoFooter
  },

  data () {
    return {
      // 准备数据
      list:[
        {id:1,name:'吃好👌！'},
        {id:2,name:'喝好👌！'},
        {id:3,name:'睡好👌！'}
      ]
    }
  }
}
</script>

<style>

</style>
