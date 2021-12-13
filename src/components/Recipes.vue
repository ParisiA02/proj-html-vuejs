<template>
    <div class="recipes-container">
       <span class="recipes-title">
           POPULAR RECIPES
       </span>
       <span class="recipes-subtitle">
           Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspendisse maximus lacus non nunc lacinia lobortis.
       </span>
       <div class="recipes-column-container">
           <div class="recipes-column column-left">
               <img src="../assets/Yogurt-Nan-600x395.jpg" alt="resturant-pic">
               <div class="column-left-title">
                   Launch Favourite with Salad, Naan And Beans
               </div>
               <div class="column-left-subtitle">
                   Bakery, Featured, Healty, Latest Recipes, Stafd Picks
               </div>
               <div class="dotted-line">
               </div>
               <div class="column-left-text">
                   Suspendisse at semper odio. Nam fringilla scelerisque tincidunt. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec tincidunt posuere ornare. Phasellus placerat odio non feugiat sollicitudin. Integer vitae elementum ex. Sed porttitor, diam eget convallis volutpat, arcu tellus facilisis nulla, id dignissim orci leo id
               </div>
               <button class="btn recipes-btn">
                   Learn More
               </button>
           </div>
           <div class="recipes-column column-right">
               <div class="recipes-img-container">
                   <img src="../assets/Mixed-fruits-400x263.jpg" alt="recipe-pic">
               </div>
               <div class="recipes-img-container">
                   <img src="../assets/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="recipe-pic">
               </div>
               <div class="recipes-img-container">
                   <img src="../assets/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="recipe-pic">
               </div>
               <div class="recipes-img-container">
                   <img src="../assets/quick-summer-drink-460x295.jpg" alt="recipe-pic">
               </div>
               <div class="recipes-img-container">
                   <img src="../assets/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="recipe-pic">
               </div>
               <div class="recipes-img-container">
                   <img src="../assets/perfect-cosmopolitan-460x295.jpg" alt="recipe-pic">
               </div>   
               <div class="recipes-img-container">
                   <img src="../assets/fi2x-6-460x295.jpg" alt="recipe-pic">
               </div>
               <div class="recipes-img-container">
                   <img src="../assets/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="recipe-pic">
               </div>
           </div>
       </div>
    </div>
</template>

<script>
export default {
  name: 'Recipes'
}
</script>

<style>
    .recipes-container{
        width: 62%;
        margin: 0 auto;
    }
    .recipes-title{
        text-align: center;
        display: block;
        font-size: 20px;
        color: #262628;
    }
    .recipes-subtitle{
        margin: 30px auto;
        width: 45%;
        text-align: center;
        display: block;
        color: #6a6b6c;
    }
    .recipes-column-container{
        width: 100%;
        margin-top: 70px;
        display: flex;
        justify-content: space-between;
    }
    .recipes-column{
        width: calc(96% /2);
        height: 100%;
    }
    .recipes-column.column-left{
        background-color: white;
    }
    .recipes-column.column-left img{
        width: 100%;
    }
    .column-left-title{
        font-size: 20px;
        margin: 30px 0 0 30px;
    }
    .column-left-subtitle{
        font-size: 15px;
        margin: 10px 0 0 30px;
    }
    .column-left-text{
        margin: 10px 30px 0 30px;
        line-height: 25px;
        font-size: 17px;
        color: #6a6b6c;

    }
    .recipes-column.column-left .dotted-line{
        width: auto;
        margin: 20px 30px 20px 30px;
    }
    .btn{
        padding: 15px;
        color: white;
        background-color: #fc7523;
        border: none;
    }
    .btn.recipes-btn{
        width: 150px;
        margin: 30px 0 50px 30px;
        border-radius: 2px;
    }
    .recipes-column.column-right{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }
    .recipes-img-container{
        width: calc(100%/2 - 12px);
        height: 170px;
        margin-bottom: 24px;
        background-color: blue;
    }
    .recipes-img-container img{
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
</style>
