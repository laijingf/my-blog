<template>
  <el-row :gutter="20">
  <el-col :span="8" v-bind:router="true">
     <router-link to="/subpageA"><el-card :body-style="{ padding:'0px'}" >
     <img src="../../assets/image/journal/076.jpg" class="image">
      <div class="text">
        <span>那个人好像一条狗</span>
      </div>
    </el-card></router-link>
  </el-col>

    <el-col :span="8">
    <el-card :body-style="{ padding:'0px'}" >
      <img src="../../assets/image/journal/219.jpg" class="image">
      <div class="text">
        <span>我知道了</span> 
      </div>
    </el-card>
  </el-col>

  <el-col :span="8">
    <el-card :body-style="{ padding:'0px'}" >
      <img src="../../assets/image/journal/637.jpg" class="image">
      <div class="text">
        <span>小朋友，看你骨骼精奇······</span> 
      </div>
    </el-card>
  </el-col>
</el-row>  
</template>

<script>
export default {
  
  }


</script>

<style scoped>
.image {
  padding:5px 8px;
    width: 95%;
    height: 250px;
    display: block; 
  }
  .el-card{
    height: 350px;
   }
  .el-card span{
    position: relative;
    bottom: 40px;
  }
</style>