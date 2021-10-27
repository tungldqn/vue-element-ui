<template>
  <div>
    <div :style="{ marginBottom: '20px' }">
      <el-button disabled>Default</el-button>
      <el-button type="primary" disabled>Primary</el-button>
      <el-button type="success" disabled>Success</el-button>
    </div>
    <div :style="{ marginBottom: '20px' }">
      <el-button plain>Default</el-button>
      <el-button type="primary" plain>Primary</el-button>
      <el-button type="success" plain>Success</el-button>
    </div>
    <div :style="{ marginBottom: '20px' }">
      <el-button plain round>Default</el-button>
      <el-button type="primary" round>Primary</el-button>
      <el-button type="success" round>Success</el-button>
    </div>
    <div :style="{ marginBottom: '20px' }">
      <el-button plain circle icon="el-icon-edit"></el-button>
      <el-button type="primary" plain circle icon="el-icon-edit"></el-button>
      <el-button type="success" plain circle icon="el-icon-edit"></el-button>
    </div>
    <div :style="{ marginBottom: '20px' }">
      <el-button type="text">Text button</el-button>
      <el-button type="text" disabled>Text button</el-button>
    </div>
    <div>
      <el-button round size="small">Default</el-button>
      <el-button type="primary" plain size="medium">Primary</el-button>
      <el-button type="success" size="big">Success</el-button>
    </div>
  </div>
</template>
