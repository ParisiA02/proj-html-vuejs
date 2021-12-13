<template>
    <div class="container">
        <Jumbotron/>
        <Journal/>
        <Recipes/>
    </div>
</template>


<script>
import Jumbotron from '../components/Jumbotron.vue'
import Journal from '../components/Journal.vue'
import Recipes from '../components/Recipes.vue'

export default {
  name: 'Main',
  components:{
      Jumbotron,
      Journal,
      Recipes
  }
}
</script>

<style>
</style>
