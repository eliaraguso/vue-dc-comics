<template>
  <div class="serie">
    <div class="serie-img" :style="`background-image: url(${serie.thumb});`"></div>
    <div class="serie-title">{{serie.series}}</div>
  </div>
</template>

<script>
export default {
  name: "Serie",
  props: ['serie']
};
</script>

<style>
.serie {
    width: calc((100% / 6) - 1rem);
    height: fit-content;
    text-align: initial;
  }
  .serie-img {
    height: 11.75rem;
    background-image: url("https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX");
    background-repeat: no-repeat;
    background-position-x: center;
    background-size: cover;
  }
  .serie-title {
    padding-top: 1.25rem;
  }

</style>