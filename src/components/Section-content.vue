<template>
  <section>
    <div class="container">
      <h1>Content goes here</h1>
    </div>
  </section>
</template>

<script>
export default {
    name: "Section_content"
}
</script>

<style lang="scss" scoped>
  @import "@/assets/style/variables.scss";

  section {
    background-color: $darkGrey;
    height: 8.25rem;
    color: white;
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }
</style>