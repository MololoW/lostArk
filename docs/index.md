<!--
 * @Author: your name
 * @Date: 2022-04-21 11:31:30
 * @LastEditTime: 2022-04-24 10:55:23
 * @LastEditors: Please set LastEditors
 * @Description: 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
 * @FilePath: \docs\README.md
-->
# Headline

> An awesome project.

<div id="box">
  <el-carousel trigger="click" height="250px">
    <el-carousel-item v-for="item in 4" :key="item">
    </el-carousel-item>
  </el-carousel>
</div>

<script>
  new Vue({
    el: '#box',
    data: {
      message: 'Hello Vue!'
    }
  })
</script>

<style>
  .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 250px;
    margin: 0;
  }

  .el-carousel__item:nth-child(2n) {
     background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
     background-color: #d3dce6;
  }
</style>

</style>

[>>指南](guide)
