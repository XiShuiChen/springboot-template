<script setup>

</script>

<template>
  <div style="width: 100vw; height: 100vh; overflow: hidden; display: flex">
    <div style="flex: 1; background-color: black">
      <el-image style="width: 100%; height: 100%;" fit="cover" src="/backjpg.jpg"/>
    </div>
    <div class="welcome-title">
      <div style="font-size: 20px; font-weight: bold">欢迎来到我的个人网站 ^_^</div>
      <div style="margin-top: 10px">请友善交流</div>
    </div>
    <div class="right-card">
      <router-view/>
    </div>
  </div>
</template>

<style scoped>
.right-card {
  width: 400px;
  z-index: 1;
  background-color: white;
}

.welcome-title {
  position: absolute;
  top: 40px;
  left: 40px;
  color: white;
  text-shadow: 0 0 10px black;
}
</style>