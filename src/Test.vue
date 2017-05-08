<template>
  <div class="test">
    <h2>Test</h2>
    <p>{{ message }}</p>
    <input v-model="message" />
    <Functional />
    <FunctionalJSX />
  </div>
</template>

<script>
import Functional from './Functional.vue'
import FunctionalJSX from './FunctionalJSX.vue'

export default {
  components: {
    Functional,
    FunctionalJSX,
  },

  data () {
    return {
      message: 'Hello world',
    }
  },
}
</script>

<style lang="less" scoped>
@color: #41b883;

.test,
input {
  font-family: sans-serif;
  font-size: 14px;
}

input {
  border: solid 1px @color;
}

input,
p {
  padding: 12px;
}

h2 {
  border-bottom: dashed 1px rgba(0, 0, 0, .1);
}
</style>
