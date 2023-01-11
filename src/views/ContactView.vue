<template>
    <NavBar/>
    <Form/>
    <Footer/>
    
</template>
<script>

    import Form from '@/components/Contact.vue'
    import NavBar from '@/components/NavBar.vue'
    import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    Form,
    Footer
  }
}
</script>
