<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <app-quote>
          <h2>{{ quoteTitle }}</h2>
          <p>A wonderful quote !!</p>
        </app-quote>
      </div>
    </div>
  </div>
</template>

<script>
import Quote from './components/Quote';
  export default {
    data: function() {
      return {
        quoteTitle: 'This is a Quote !!!'
      }
    },
    components: {
      appQuote: Quote
    }
  }
  </script>

 <style scoped>
 </style>