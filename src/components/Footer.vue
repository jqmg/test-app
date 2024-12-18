<template>
  <footer>
    <p>&copy; {{ currentYear }}</p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {
      currentYear: new Date().getFullYear()
    }
  }
}
</script>

<style scoped>
footer {
  margin-top: 2em;
  padding: 1em;
  background-color: #1a1a1a;
  color: #fff;
  text-align: center;
}
</style>
