<template>
  <Header />
  <Cards />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Cards from './components/Cards.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    Header,
    Cards,
    Footer
  }
}
</script>