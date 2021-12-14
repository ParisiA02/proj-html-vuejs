<template>
    <div class="container">
        <Jumbotron/>
        <Journal/>
        <Recipes/>
        <Collection/>
        <Blog/>
        <Subscribe/>
    </div>
</template>


<script>
import Jumbotron from '../components/Jumbotron.vue'
import Journal from '../components/Journal.vue'
import Recipes from '../components/Recipes.vue'
import Collection from '../components/Collection.vue'
import Blog from '../components/Blog.vue'
import Subscribe from '../components/Subscribe.vue'

export default {
  name: 'Main',
  components:{
      Jumbotron,
      Journal,
      Recipes,
      Collection,
      Blog,
      Subscribe
  }
}
</script>

<style>
</style>
