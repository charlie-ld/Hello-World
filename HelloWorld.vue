<div id="app">
  <p>{{ message }}</p>
  <input v-model="message">
</div>


<script>
new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue.js!'
  }
})
</script>