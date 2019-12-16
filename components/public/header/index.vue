<template>
  <el-row :gutter="0" class="m-header">
    <el-col :span="4">
      <!-- 城市定位 -->
      <geo/>
    </el-col>
    <el-col :span="6">
      <!-- 用户 -->
      <user/>
    </el-col>
    <el-col :span="14">
      <my-nav/>
    </el-col>
  </el-row>
</template>
<script>
import geo from "./geo";
import user from './user';
import myNav from './nav';
export default {
  components: {
    geo,
    user,
    myNav
  }
};
</script>

<style lang = "scss">
  @import "@/assets/css/public/header/index.scss";
</style>
