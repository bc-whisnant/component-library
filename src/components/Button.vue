<template>
  <div class="center">
    <div>
      <h1>Testing</h1>
      <button @click="increaseCount">Click Me</button>
      <p>{{ count }}</p>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        count: 0
      }
    },
    methods: {
      increaseCount() {
        this.count++
      }
    }
  }
</script>

<style scoped>
  .center {
    text-align: center;
  }
</style>
