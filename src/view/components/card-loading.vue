<template>
  <div class="loading-container">
    <!-- Lottie 动画组件 -->
    <dotlottie-wc 
      src="https://lottie.host/8d6494b9-32bf-40e2-af97-5ca3c9d59bdc/qpUX4OgRii.lottie" 
      style="width: 300px; height: 300px;" 
      autoplay 
      loop>
    </dotlottie-wc>
  </div>
</template>

<script setup lang="ts">
// 旧的图片读取逻辑已删除，现在不需要任何脚本
</script>

<style lang="scss" scoped>
.loading-container {
  display: flex;
  justify-content: center; /* 水平居中 */
  align-items: center;     /* 垂直居中 */
  width: 100%;
  min-height: 200px;       /* 保持最小高度，防止高度塌陷 */
}
</style>
