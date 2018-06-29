<template lang='pug'>
  div
    el-button(@click="visible = true") Button
    <el-dialog :visible.sync="visible" title="Hello world">
      <p>Try Element</p>
    </el-dialog>
</template>

<script type='text/javascript'>
export default {
  data() {
    return {
      visible: false
    }
  },
  components: {}
}
</script>

<style scoped lang='stylus'>
</style>
