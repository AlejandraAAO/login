<template>
  <el-row >
  
  

  <el-container>

  <el-main>
    <el-row type="flex" justify="center">
    <el-row :span="6" v-for="(o, index) in 1" :key="o" :offset="index > 0 ? 1 : 0">
    <el-card :body-style="{display:'flex', padding: '0px'}">
      <img src="../assets/verde.jpg" class="image">
      <div style="padding: 14px;">
        <h5>Bienvenido</h5>
        <div class="bottom clearfix">
          
          <el-button type="text" class="button">Operating button</el-button>
        </div>
      </div>
    </el-card>
  </el-row>
</el-row>
  </el-main>
</el-container>
 
</el-row>
</template>

<script>
export default {
  name: 'Test'
}
</script>

<style scoped>
.image {
  width: 11rem;
  height: 14rem;;
}
   .el-row {
    margin-bottom: 20px;
    
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>

