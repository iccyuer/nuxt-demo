<template>
  <div>
    <h2 v-html="titleMsg"></h2>
  </div>
</template>

<script>
export default {
  props: {
    titleMsg: {
      type: String,
      default: ''
    }
  }
}
</script>

<style>

</style>
