<template>
  <div class="container">
    <app-quote-grid :quotes="quotes"></app-quote-grid>
  </div>
</template>

<script>
import QuoteGrid from "./components/QuoteGrid.vue";
import Quote from "./components/Quote.vue";
export default {
  data() {
    return {
      maxQuotes: 10,
      quotes: ["Just a Quote to see something"],
    };
  },
  components: {
    appQuoteGrid: QuoteGrid,
  },
};
</script>

<style>
</style>
