<template>
  <div id="app">
    <div id="content">
      <Nav />
      <Content />
      <Footer />
    </div>
  </div>
</template>
<script>
import Nav from './components/Nav.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Content,
    Footer
  }
}
</script>
<style>
</style>
