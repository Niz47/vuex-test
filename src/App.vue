<template>
  <div id="app">
    <!-- <product-list-one v-bind:products="products"></product-list-one>
    <product-list-two v-bind:products="products"></product-list-two> -->
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>

  </div>
</template>

<script>
import ProductListOne from './components/product-list-one.vue';
import ProductListTwo from './components/product-list-two.vue';

export default {
  components: {
    'product-list-one': ProductListOne,
    'product-list-two': ProductListTwo,
  },
  name: 'app',
  data () {
    return {

    }
  }
}
</script>

<style>
body{
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  color: #555;
}
</style>
