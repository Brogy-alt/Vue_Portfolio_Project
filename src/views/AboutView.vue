<template>
   <NavBar/>
   <About/>
   <Resume/>
   <Skills/>
   <Footer/>
   
  
</template>
<script>
import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'
import About from '@/components/About.vue'
import Resume from '@/components/Resume.vue'
import Skills from '@/components/Skills.vue'


export default {
  name: 'HomeView',
  components: {
    NavBar,
    About,
    Resume,
    Skills,
    Footer
  }
}

</script>

