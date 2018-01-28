<template>
  <div class="paging-wrap">
    <el-pagination
      background
      layout="prev, pager, next"
      :total="1000">
    </el-pagination>
  </div>
</template>

<script>
export default {
  name: 'Paging',
  data () {
    return {

    }
  }
}
</script>

<style lang="scss" scope>
.paging-wrap {
  margin: 20px auto;
}
</style>
