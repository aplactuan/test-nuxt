<template>
  <section class="container">
    <h2>
      <nuxt-link to="/products">Go to products</nuxt-link>
    </h2>
  </section>
</template>

<script>
export default {
  data() {
    return {
      userId: ''
    };
  },
  methods: {
    goToUser() {
      this.$router.push('/users/' + this.userId);
    }
  }
}
</script>
