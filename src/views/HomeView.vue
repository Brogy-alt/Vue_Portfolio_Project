<template>

  <NavBar/>
  <HomePage/>
  <Footer/>
  
</template>

<script>
// @ is an alias to /src

import NavBar from '@/components/NavBar.vue'
import HomePage from '@/components/HomePage.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    HomePage,
    Footer
  }
}
</script>
