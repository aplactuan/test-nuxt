<template>
  <div class="container">
    <nuxt-link :to="{name: 'products-pid', params: {pid: 1}}">Product 1</nuxt-link>
    <nuxt-link :to="{name: 'products-pid', params: {pid: 2}}">Product 2</nuxt-link>
  </div>
</template>
