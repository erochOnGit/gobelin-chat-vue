<template>
  <div class="container">
    <Square/>
  </div>
</template>

<script>
import Square from './Square.vue'
export default {
  components: {
    Square
  },
  props: {
    name: {
      type: String,
      required: true
    }
  }
}

</script>

<style lang="stylus" scoped>
.container {
  position: relative;
  left: 0vw;
  top: 0vh;
  width: 100vw;
  height: 100vw;
  background: black;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
