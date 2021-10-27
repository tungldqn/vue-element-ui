<template>
  <div>
    <el-row>
      <el-col :span="24">
        <div :style="{ background: 'red' }">Hello 24</div>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="12" :style="{ background: 'red' }">Col 12</el-col>
      <el-col :span="12" :style="{ background: 'red' }">Col 10</el-col>
    </el-row>
    <div
      :style="{
        padding: '0 10px',
      }"
    >
      <el-row :gutter="20" type="flex" justify="center">
        <el-col :span="3">6</el-col>
        <el-col :span="3">6</el-col>
        <el-col :span="3">6</el-col>
        <el-col :span="3">6</el-col>
      </el-row>

      <!-- <el-row :gutter="20">
        <el-col :span="6">6</el-col>
        <el-col :span="12">12</el-col>
        <el-col :span="6">6</el-col>
      </el-row> -->

      <!-- <el-row :gutter="20">
        <el-col :span="6">6</el-col>
        <el-col :span="12" :offset="6">12</el-col>
        <el-col :span="6">6</el-col>
      </el-row> -->
    </div>
  </div>
</template>

<script></script>
<style lang="scss"></style>
