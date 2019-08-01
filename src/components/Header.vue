<template>
  <div class="header flex flex-center-between">
    <p class="title">后台管理系统</p>
    <div class="flex">
      <el-dropdown>
        <span class="el-dropdown-link">
          <span>admin</span>
          <i class="el-icon-arrow-down el-icon--right"></i>
        </span>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item>账号信息</el-dropdown-item>
          <el-dropdown-item>退出登录</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
      <el-dropdown>
        <el-badge :value="12" class="item">
          <i class="el-icon-bell animated swing" style="font-size:20px"></i>
        </el-badge>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item>微信用户CCC下单了，马上处理》</el-dropdown-item>
          <el-dropdown-item>收到微信用户CCC的回馈》</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped lang="scss">
.header{
  width: 100%;
  height: 60px;
  padding: 0 40px 0 20px;
  background: #409EFF;
  color: #fff;
  .title{
    font-size: 20px;
  }
}
.el-dropdown{
  color: #fff;
  margin-right:20px;
}
.swing{
   animation-iteration-count: infinite;
}
</style>
