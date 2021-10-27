<template>
  <div class="hello">
    <h1>{{ message }}</h1>
    <button v-on:click="reverseMessage"> Say hi!</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      message: 'Bruno - Emmanuel - Facu - Juan App'
    }
  },
  methods: {
    reverseMessage: function () {
      this.message = 'HI'
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: normal;
}
a {
  color: #42b983;
}
</style>
