<template>
  <div id="bottomNav" >
    <!--<el-button round><router-link to="/pageA">旅行日志</router-link></el-button>
    <el-button round><router-link to="/pageB">观影日志</router-link></el-button>
    <el-button round><router-link to="/pageC">生活日志</router-link></el-button>-->
    <router-link to="/pageA" class="tab">旅行日志</router-link>
    <router-link to="/pageB" class="tab">观影日志</router-link>
    <router-link to="/pageC" class="tab">生活日志</router-link>
  </div>
</template>

<script>
export default{
    
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #bottomNav {
    display: flex;/*垂直居中*/
    width: 900px;
    height: 35px;
    line-height: 35px;
    text-align: center;
    position:fixed;
    right:60px;
    bottom: 90px;
  }

  .tab {
    flex: 1;
    text-align:center;
    margin-right: 50px; 
    border-radius:10px;
    background:#409EFF;
    color: #fff;
  }
</style>