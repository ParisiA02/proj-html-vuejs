<template>
    <div class="container">
        <Jumbotron/>
        <Journal/>
        <Recipes/>
        <Collection/>
    </div>
</template>


<script>
import Jumbotron from '../components/Jumbotron.vue'
import Journal from '../components/Journal.vue'
import Recipes from '../components/Recipes.vue'
import Collection from '../components/Collection.vue'

export default {
  name: 'Main',
  components:{
      Jumbotron,
      Journal,
      Recipes,
      Collection
  }
}
</script>

<style>
</style>
