<!--
 * @Author: your name
 * @Date: 2022-04-21 11:31:30
 * @LastEditTime: 2022-04-28 09:52:42
 * @LastEditors: Please set LastEditors
 * @Description: 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
 * @FilePath: \docs\README.md
-->

<div id="box" class="box">
  <el-carousel trigger="click">
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
  /* .box {
    width: 100%;
    height: 100%;
  } */

  .el-carousel--horizontal {
    width: 80%;
    margin: auto;
  }

  .el-carousel__container {
  }

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
