<template>
<el-row :gutter="20">
  <el-col :span="8">
    <el-card :body-style="{ padding:'0px'}" >
      <img src="../../assets/image/journal/plain.jpg" class="image">
      <div>
        <span>一望无际的平原</span> 
      </div>
    </el-card>
  </el-col>

    <el-col :span="8">
    <el-card :body-style="{ padding:'0px'}" >
      <img src="../../assets/image/journal/lake.jpg" class="image">
      <div >
        <span>一面是湖一面沙漠</span> 
      </div>
    </el-card>
  </el-col>

  <el-col :span="8">
    <el-card :body-style="{ padding:'0px'}" >
      <img src="../../assets/image/journal/flower-sea.jpg" class="image">
       
       <span>面朝大海，春暖花开</span> 
     
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