<template>
  <el-aside class='left'>
    <el-menu>
      <el-submenu index="1">
        <template slot="title"><i class="el-icon-menu"></i>用户中心</template>
        <el-menu-item-group>
          <el-menu-item index="1-1">选项1</el-menu-item>
          <el-menu-item index="1-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
      <el-submenu index="2">
        <template slot="title"><i class="el-icon-menu"></i>客户案例</template>
        <el-menu-item-group>
          <el-menu-item index="2-1">选项1</el-menu-item>
          <el-menu-item index="2-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
      <el-submenu index="3">
        <template slot="title"><i class="el-icon-setting"></i>客户信息</template>
        <el-menu-item-group>
          <el-menu-item index="3-1">选项1</el-menu-item>
          <el-menu-item index="3-2">选项2</el-menu-item>
        </el-menu-item-group>
        <el-submenu index="3-3">
           <template slot="title">选项3</template>
          <el-menu-item index="3-3-1">选项3-1</el-menu-item>
        </el-submenu>
      </el-submenu>
    </el-menu>
  </el-aside>
</template>

<script>
export default {
  data() {
    return {};
  },
  components: {},
};
</script>

<style scoped>
.left{
  width: 200px;
  background: #ccc;
}
.el-submenu{
  border: 1px solid #333;
}
.el-menu-item{
  border: 1px solid #333;
}
</style>
