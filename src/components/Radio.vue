<template>
  <div>
    <el-radio v-model="radio" label="1">Option A</el-radio>
    <el-radio v-model="radio" label="2">Option B</el-radio>
    <el-radio v-model="radio" label="3" disabled>Option C</el-radio>

    <div>
      <el-radio-group v-model="radio" size="mini">
        <el-radio-button label="1">Option A</el-radio-button>
        <el-radio-button label="2">Option B</el-radio-button>
        <el-radio-button label="3">Option C</el-radio-button>
      </el-radio-group>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      radio: "1",
    };
  },
};
</script>
