<template>
  <div id='app'>
<myHeader />
<MyGoods><MyCount /></MyGoods>

<MyFooter />
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import MyGoods from './components/MyGoods.vue'
import MyFooter from './components/MyFooter.vue'
import MyCount from './components/MyCount.vue'
export default {
  data () {
    return {

    }
  },
components:{
  myHeader,
  MyGoods,
  MyFooter,
  MyCount
  },
  created () {

  },

  methods: {

  }
}
</script>

<style scoped>
#app{
  padding-top:50px
}
</style>
