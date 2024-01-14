<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Foo />
    <Bar />
  </div>
</template>

<script>
import { Foo, Bar } from 'web-vite-vue-v2'

export default {
  components: {
    Foo,
    Bar
  }
}
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
