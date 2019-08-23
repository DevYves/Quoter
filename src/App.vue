<template>
  <div id="app">
    <h1 class="title">Quoter</h1>
    <div class="progress-bar-outer">
      <div class="progress-bar-inner">1/10</div>
    </div>
    <form class="quote-form" action method="post" titl="Quote">
      <label for="quote">Quote</label>
      <input class="quote-text" type="text" name="quote" id />
      <div class="button-container">
        <input type="submit" value="Random" />
        <input type="submit" value="Add Quote" />
      </div>
    </form>

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
    <div class="footer-info">Info: click on a quote to delete it</div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#app {
  align-content: center;
  align-items: center;
  display: flex;
  flex-flow: column nowrap;
  height: 100%;
  justify-content: start;
}
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
.quote-text {
  border-radius: 5px;
  height: 90%;
  margin: 10px;
  width: 100%;
}
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
.footer-info {
  background-color: turquoise;
  border-radius: 5px;
  margin-bottom: 25px;
  padding: 10px;
  text-align: center;
  width: 50%;
}
.title {
  height: 10%;
}
</style>