<script>
export default {
  functional: true,
  render (h) {
    return h('h1', 'Hello world')
  },
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>

<style>
h1 {
  border-bottom: solid 1px rgba(0, 0, 0, .1);
}
</style>
