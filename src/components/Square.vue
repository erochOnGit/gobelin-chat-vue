<template>
  <div class="square">
    <input type="text">
  </div>
</template>
<script>

</script>

<style lang="stylus" scoped>
.square {
  position: relative;
  left: 0vw;
  top: 0vh;
  width: 20vw;
  height: 20vw;
  background: white;
  transform: rotate(0deg);
  transition: transform 20s;
}

.square input {
  border: none;
}
</style>
