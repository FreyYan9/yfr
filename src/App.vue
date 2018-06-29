<template lang='pug'>
    .el-container
      .el-header
        Header
      .el-main 
        router-view
      .el-footer
</template>
 
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Header from '@/components/Header.vue' // @ is an alias to /src

export default {
  components: {
    Header
  }
}
</script> 


<style lang="stylus">
</style> 