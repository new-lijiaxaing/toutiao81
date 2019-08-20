<template>
<!-- 最外层容器 -->
  <el-container>
    <!-- 左侧布局 -->
    <el-aside style="width:200px;height:100vh; background-color:#323745;">
      <!-- 左侧菜单 -->
      <layout-aside></layout-aside>
    </el-aside>

    <!-- 右侧布局 -->
  <el-container>
    <!-- 头部区域 -->
    <el-header>
      <layout-header></layout-header>
    </el-header>
    <!-- 中间区域 -->
    <el-main>
      右侧
    </el-main>
  </el-container>
  </el-container>
</template>

<script>

export default {
  components: {

  }
}
</script>

<style>

</style>
