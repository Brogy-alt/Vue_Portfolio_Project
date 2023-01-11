<template>
   <NavBar/>
   <Testimonials/>
   <Projects/>
   <Footer/>
   
  
</template>
<script>
import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'
import Projects from '@/components/Projects.vue'
import Testimonials from '@/components/Testimonials.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    Projects,
    Testimonials,
    Footer
  }
}

</script>