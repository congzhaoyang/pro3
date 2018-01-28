<template>
  <el-row>
    <el-col :span="24">
      <div class="grid-content bg-purple-dark">
        <ArticleBar/>
        <ArticleBar/>
        <ArticleBar/>
        <ArticleBar/>
        <ArticleBar/>
        <ArticleBar/>
        <ArticleBar/>
        <ArticleBar/>
        <Paging/>
        <Footer/>
      </div>
    </el-col>
  </el-row>
</template>

<script>
import ArticleBar from '../ArticleBar/ArticleBar'
import Paging from '../Paging/Paging'
import Footer from '../Footer/Footer'

export default {
  name: 'Index',
  data () {
    return {

    }
  },
  components: {
    ArticleBar,
    Paging,
    Footer
  }
}
</script>

<style lang="scss" scope>

</style>
