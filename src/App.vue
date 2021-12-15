<template>
  <div id="app">
    <Header :socials="socials" :links="links"/>
    <Main/>
    <Footer :socials="socials" :contacts="contacts" :links="links"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  },
  data(){
    return{
      links:["Home","Recipes","Places","Blog","About","Contact"],
      socials:["fab fa-facebook-f","fab fa-instagram","fab fa-twitter","fab fa-youtube"],
      contacts:{
        icon:[
          "fas fa-map-marker-alt",
          "fas fa-phone",
          "fas fa-envelope" 
        ],
        text:[
          "775 New York Ave, Brooklyn, Kings, New York 11203",
          "+ 0100-505-0000",
          "info@your-domain.com"
        ]

      }
    }
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #F5F5F1;
}
</style>
