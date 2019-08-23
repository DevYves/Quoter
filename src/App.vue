<template>
  <div id="app">
    <h1 class="title">Quoter</h1>
    <progress-bar></progress-bar>
    <quote-form></quote-form>
    <quote-container></quote-container>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Footer from "./components/Footer";
import ProgressBar from "./components/ProgressBar";
import QuoteContainer from "./components/QuoteContainer";
import QuoteForm from "./components/QuoteForm";
export default {
  components: {
    "app-footer": Footer,
    "progress-bar": ProgressBar,
    "quote-container": QuoteContainer,
    "quote-form": QuoteForm
  }
};
</script>

<style>
#app {
  align-content: center;
  align-items: center;
  display: flex;
  flex-flow: column nowrap;
  height: 100%;
  justify-content: flex-start;
}

.title {
  height: 10%;
}
</style>
