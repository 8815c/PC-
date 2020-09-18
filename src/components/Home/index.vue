<template>
  <div>
    <el-radio-group v-model="isCollapse" style="margin-bottom: 20px;">
      <el-radio-button :label="false">展开</el-radio-button>
      <el-radio-button :label="true">收起</el-radio-button>
    </el-radio-group>
    <el-menu
      default-active="1-4-1"
      class="el-menu-vertical-demo"
      @open="handleOpen"
      @close="handleClose"
      :collapse="isCollapse"
    >

        <el-menu-item index="1">
        <i class="el-icon-menu"></i>
        <span slot="title">首页</span>
      </el-menu-item>

     <el-submenu index="2">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span slot="title">商品</span>
        </template>
      </el-submenu>

      <el-submenu index="3">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span slot="title">订单</span>
        </template>
      </el-submenu>

      <el-submenu index="4">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span slot="title">营销</span>
        </template>
      </el-submenu>

        <el-submenu index="5">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span slot="title">权限</span>
        </template>
      </el-submenu>
    </el-menu>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isCollapse: true,
    };
  },
 
};
</script>

<style lang="less" scoped>
.el-menu-vertical-demo:not(.el-menu--collapse) {
  width: 200px;
  min-height: 400px;
}
</style>
