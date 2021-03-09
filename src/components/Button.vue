<template lang="html">
  <button :style="{background: color}" class="btn">{{text}}</button>

</template>

<script>
export default {
  name: 'Button',
  props: {
    text: String,
    color: String
  }
}
</script>

<style lang="css" scoped>
</style>
