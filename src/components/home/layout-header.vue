<template>
<!-- 用el-row 和el-col布局 -->
<el-row class="layout-header" type="flex" justify="space-between">
    <el-col :span="16" class="left-geader">
        <i class="el-icon-s-unfold"></i>
        <span>中国持名品牌(管理)有限公司</span>
    </el-col>
    <el-col class="layout-right" :span="3">
        <img src="../../assets/img/avatar.jpg" alt="">
        <!-- 两个插槽 一个具名插槽 一个匿名插槽 -->
        <el-dropdown trigger="click">
            <!-- 匿名插槽 -->
            <span class="el-dropdown-link">
                我是,你猜
            </span>
            <i class="el-icon-arrow-down el-icon--right"></i>
            <!-- 具名插槽 -->
            <el-dropdown-menu slot="dropdown">
                <el-dropdown-item>个人信息</el-dropdown-item>
                <el-dropdown-item>git地址</el-dropdown-item>
                <el-dropdown-item>退出</el-dropdown-item>
            </el-dropdown-menu>
        </el-dropdown>
    </el-col>
</el-row>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.layout-header{
    padding: 12px 0;
    .left-geader{
        display: flex;
        align-items: center;
        i{
            font-size: 20px;
            margin-right: 4px;
        }
    }
    .layout-right{
    display: flex;
    align-items: center;
    img{
        width: 40px;
        height: 40px;
        border-radius:50%;
        margin-right: 10px;
    }
    }
}

</style>
