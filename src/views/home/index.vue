<script setup lang="ts">
const handleClick = () => {
  console.log(`🍍🙏🍍👉:    用户信息`)
}
</script>

<template>
  <div class="home-container">
    <div class="header-content" @click="handleClick">2023年7月22日</div>
  </div>
</template>

<style lang="less" scoped>
.home-container {
  .header-content {
    height: 40px;
    line-height: 40px;
    background: #d9d9d9;
    text-align: center;

    font-size: 15px;
    font-family:
      PingFang SC-Medium,
      PingFang SC;
    font-weight: 500;
    color: #171717;
  }
}
</style>
