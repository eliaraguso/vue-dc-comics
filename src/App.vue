<template>
  <div id="app">
    <Header/>
    <main>
      <Section_content/>
      <Section_services/>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Section_content from '@/components/Section-content.vue'
import Section_services from '@/components/Section-services.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Section_content,
    Section_services,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  
}
</style>
