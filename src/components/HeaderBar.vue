<template>
  <el-container>
    <el-header style="text-align: right; font-size: 12px">
      <el-dropdown>
        <i class="el-icon-setting" style="margin-right: 15px"></i>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item>查看</el-dropdown-item>
          <el-dropdown-item>新增</el-dropdown-item>
          <el-dropdown-item>删除</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
      <span>王小虎</span>
    </el-header>
  </el-container>
</template>

<script>
export default {
  name: "HeaderBar",
  data() {
    return {
      options: [
        {
          value: "001",
          label: "修改",
        },
        {
          value: "002",
          label: "新增",
        },
        {
          value: "003",
          label: "删除",
        },
      ],
      value: "",
    };
  },
};
</script>

<style scoped>
.el-header {
  background: skyblue;
  width: 100%;
  line-height: 60px;
}

</style>
