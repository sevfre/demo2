<template>
  <div>
    {{msg}}<br>
    <el-button type="success">成功按钮</el-button>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Home',
  data(){
    return{
      msg:"这是主页"
    }
  },
  mounted(): void {
    console.log("aaa")
  }
}
</script>
