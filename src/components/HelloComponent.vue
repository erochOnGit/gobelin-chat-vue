<template>
  <Square/>
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
