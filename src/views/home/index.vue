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
      头部区域
    </el-header>
    <!-- 中间区域 -->
    <el-main>
      右侧
    </el-main>
  </el-container>
  </el-container>
</template>

<script>
import layoutAside from '../../components/home/layout-aside'
export default {
  components: {
    'layout-aside': layoutAside
  }
}
</script>

<style>

</style>
