<template>
  <div class="text-center">
    <h1>
      <i-mdi-human-greeting-variant style="padding-right: 10px" class="text-black-40" />
      {{ msg }}
    </h1>
    <p>
      A starter project using
      <a href="https://vuejs.org/" target="_blank">Vue 3</a>.
    </p>
  </div>
</template>

<script>
export default {
  props: {
    msg: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped></style>
