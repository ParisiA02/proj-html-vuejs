<template>
  <div class="collection-container">
      <div class="collection-title title">
          CULINARY COLLECTION
      </div>
      <div class="collection-subtitle subtitle">
          Aliquam erat volutpat. Ut quis ligua a magna blandit finibus. Suspendisse maximus lacus non nunc lacinia lobortis.
      </div>
      <div class="card-container">
          <div class="icon-container">
                <img src="../assets/drinks-recipes.png" alt="icon-pic"> 
              <div class="icon-text">
                  DRINKS
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/soups-recipes.png" alt="icon-pic">
              <div class="icon-text">
                  SOUPS
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/baking-recipes.png" alt="icon-pic">
              <div class="icon-text">
                  BAKERY
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/dinner-recipes.png" alt="icon-pic"> 
              <div class="icon-text">
                  DINNER
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/healthy-recipes.png" alt="icon-pic">
              <div class="icon-text">
                  HEALTY
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/staff-picks.png" alt="icon-pic">
              <div class="icon-text">
                  STAFF PICKS
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/premium-recipes.png" alt="icon-pic">
              <div class="icon-text">
                  APPETISERS
              </div>
          </div>
          <div class="icon-container">
              <img src="../assets/quick-easy-recipes.png" alt="icon-pic">
              <div class="icon-text">
                  QUICK & EASY
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Collection'
}
</script>

<style>
    .collection-container{
        width: 62%;
        margin: 0 auto;
    }
    .collection-title{
        margin-top: 200px;
    }
    .card-container{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }
    .icon-container{
        width: calc(90% / 4);
        height: 170px;
        margin-bottom: 30px;
        background-color: white;
        text-align: center;
        box-shadow: 0px 0px 10px 1px rgba(0,0,0,0.10);
    }
    .icon-container img{
        width: 100px;
        height: 100px;
        margin: 20px 0 10px 0;
    }
</style>
