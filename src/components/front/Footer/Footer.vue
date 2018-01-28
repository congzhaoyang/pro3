<template>
  <el-row>
    <el-col :span="24">
      <div class="grid-content bg-purple-dark">
        <div class="content">
          Copyright © My Blog 2017-2018
        </div>
      </div>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      
    }
  }
}
</script>

<style lang="scss" scope>
.content {
  font-size: 14px;
  color: #4A4A4A;
  margin: 20px auto 40px;
}
</style>
