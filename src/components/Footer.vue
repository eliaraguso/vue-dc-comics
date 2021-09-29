<template>
  <footer>
    <div id="footer-top">
      <div class="container">
        <h1>Footer</h1>
      </div>
    </div>
    <div id="footer-bottom"></div>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>
  
<style lang="scss" scoped>
@import "@/assets/style/variables";
  footer {
    height: 30rem;
  }

  #footer-top {
    height: 23.125rem;
    background-image: url(../assets/images/footer-bg.jpg);
  }
  #footer-bottom {
      height: 6.875rem;
      background-color: $lightGrey;
    }
</style>