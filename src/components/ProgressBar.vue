<template>
  <div class="progress-bar-outer">
    <div class="progress-bar-inner">1/10</div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.progress-bar-outer {
  background-color: #ececec;
  border-radius: 5px;
  margin: 10px;
  width: 50%;
}
.progress-bar-inner {
  background-color: turquoise;
  border-radius: 5px 0px 0px 5px;
  padding: 2px;
  text-align: center;
  transition: width 0.3s ease;
  width: 10%;
}
</style>
