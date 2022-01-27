<template>
  <div class="container">
    Show data for {{ pid }}
  </div>
</template>

<script>
  export default {
    computed: {
      pid() {
        return this.$route.params.pid
      }
    }
  }
</script>
