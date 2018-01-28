<template>
  <el-row>
    <el-col :span="24">
      <div class="grid-content bg-purple-dark">
        <div class="wrap">
          <article class="post">
            <header class="post-header">
              <h2 class="post-title">
                <a href="/blog/ji-vueda-xing-biao-dan-xiang-mu-de-ge-xing-neng-wen-ti/">记vue大型表单项目的一个性能问题</a>
              </h2>
            </header>
            <section class="post-excerpt">
              <p>问题场景 身为一个表单表格工程师，自然日复一日的写着表单表格，本以为已经没啥难点的时候转眼间就来了一个有意思的情况，在超大量 数据绑定在 vue 的时候出现了表单操作起来卡顿的情况。 </p>
            </section>
            <footer class="post-meta">
              <time class="post-date" datetime="2017-10-27">2018-01-28</time>
              <span style="margin-left:20px;">访问数：3724</span>
            </footer>
          </article>
        </div>
      </div>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: 'ArticleBar',
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scope>
.wrap {
  position: relative;
  width: 80%;
  max-width: 710px;
  margin: 3rem auto 0;
  padding-bottom: 3rem;
  border-bottom: #EBF2F6 1px solid;
  word-wrap: break-word;
  .post {
    text-align: left;
    .post-header {
      font-family: 'Avenir Next',Avenir,'Helvetica Neue',Helvetica,'Hiragino Sans GB','Microsoft YaHei',"微软雅黑",STHeiti,'WenQuanYi Micro Hei',SimSun,sans-serif;
      letter-spacing: 0.01rem;
      margin-bottom: 10px;
      .post-title {
        color: #2E2E2E;
        line-height: 1.15em;
        font-family: "Open Sans", sans-serif;
        text-rendering: geometricPrecision;
        a {
          text-decoration: none;
          color: #4A4A4A;
          font-size: 24px;
          font-weight: bold;
        }
      }
    }
    .post-excerpt {
      margin: 20px 0 16px;
      p {
        color: #3A4145;
        font-family: 'Avenir Next',Avenir,'Helvetica Neue',Helvetica,'Hiragino Sans GB','Microsoft YaHei',"微软雅黑",STHeiti,'WenQuanYi Micro Hei',SimSun,sans-serif;
        letter-spacing: 0.01rem;
        font-size: 0.9em;
        line-height: 1.7em;
      }
    }
    .post-meta {
      font-family: "Open Sans", sans-serif;
      font-size: 1.5rem;
      line-height: 16px;
      color: #9EABB3;
      font-size: 16px;
    }
  } 
}
</style>
