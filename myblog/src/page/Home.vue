<template>
 
  <el-row :gutter="20">

   <el-col :span="24" class="warp-breadcrum">
      <el-breadcrumb separator="/">
        <el-breadcrumb-item :to="{ path: '/movie' }"><b>首页</b></el-breadcrumb-item>
      </el-breadcrumb>
   </el-col>
  
   <el-col :span="8">
    <el-card :body-style="{ padding:'0px'}" >
      <img src="../assets/image/home/plain.jpg" class="image">
      <div class="text">
        <span>一望无际的平原</span>
        
      </div>
    </el-card>
   </el-col>

   <el-col :span="8">
    <el-card :body-style="{ padding: '0px' }">
      <img src="../assets/image/home/lake.jpg" class="image">
      <div class="text">
        <span>一面是湖一面沙漠</span>
        
      </div>
    </el-card>
   </el-col>

   <el-col :span="8">
    <el-card :body-style="{ padding: '0px' }">
      <img src="../assets/image/home/076.jpg" class="image">
      <div class="text">
        <span>那个人好像一条狗</span>
      </div>
    </el-card>
   </el-col>

</el-row>
</template>

<script>
export default {
  data() {
    return {
      currentDate: new Date()
    };
  }

};
</script>

<style scoped>
.warp-breadcrum{
  margin-bottom: 20px; 
}
 .image {
 	  padding:5px 8px;
    width: 95%;
    height: 250px;
    display: block; 
  }
  .el-card{
  	height: 350px;
  }
 .text{
 	margin: -30px 0;
 }
</style>