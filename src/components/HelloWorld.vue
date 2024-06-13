<template>
  <div class="text-center">
    <h1>
      <i-mdi-human-greeting-variant style="padding-right: 10px" class="text-black-50" />
      {{ msg }}
    </h1>
    <p>
      You’ve successfully created a project with
      <a href="https://vitejs.dev/" target="_blank" rel="noopener">Vite</a> +
      <a href="https://vuejs.org/" target="_blank" rel="noopener">Vue 3</a>.
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

<style scss scoped></style>
