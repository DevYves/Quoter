<template>
  <form class="quote-form" action method="post" titl="Quote">
    <label for="quote">Quote</label>
    <input class="quote-text" type="text" name="quote" id />
    <div class="button-container">
      <input type="submit" value="Random" />
      <input type="submit" value="Add Quote" />
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style scoped>
.quote-text {
  border-radius: 5px;
  height: 90%;
  margin: 10px;
  width: 100%;
}
.button-container {
  display: flex;
  justify-content: space-evenly;
  width: 100%;
}
.quote-form {
  align-items: center;
  display: flex;
  flex-flow: column nowrap;
  height: 20%;
  justify-content: center;
  width: 50%;
}
</style>
