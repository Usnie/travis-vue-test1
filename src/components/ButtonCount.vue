<template>
  <div>
    <h3>Welcome to button count application</h3>
    <p>Button count is: {{count}}</p>
    <button @click="changeCount">click demo</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      count: 0
    }
  },
  methods: {
    changeCount () {
      this.count += 1 // count increment
    }
  }
}
</script>
