<template>
  <div class="quote-container">
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
    <div class="quote">Test quote</div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.quote-container {
  align-items: flex-start;
  display: flex;
  flex-wrap: wrap;
  height: 60%;
  justify-content: center;
  margin-top: 10px;
  width: 80%;
}
.quote {
  border: 1px solid black;
  margin: 10px;
  text-align: center;
}
</style>
