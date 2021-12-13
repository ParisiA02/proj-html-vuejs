<template>
  <div class="journal-container">
      <div class="journal-title-container">
          <div class="dotted-line">
          </div>
          <div class="journal-title">
              FOODIE JOURNAL
          </div>
          <div class="dotted-line">
          </div>
      </div>
        <div class="journal-column">
            <div class="journal-img">
                <img src="../assets/single-post-img3-400x263.jpg" alt="resturant-img">
            </div>
            <div class="journal-column-title">
                Food Corner: Top Japanese Restaurants for Sushi
            </div>
            <div class="journal-column-date">
                By admin | March 25th, 2019
            </div>
        </div>
        <div class="journal-column">
            <div class="journal-img">
                <img src="../assets/fi-roundup-400x263.jpg" alt="resturant-img">      
            </div>
            <div class="journal-column-title">
                Roundup: My New Favourite Recipes For Healty Living
            </div>
            <div class="journal-column-date">
                By admin | March 25th, 2019
            </div>
        </div>
        <div class="journal-column">
            <div class="journal-img">
                <img src="../assets/fi-toasts-400x263.jpg" alt="resturant-img">
            </div>
            <div class="journal-column-title">
                Why These Toasts with Tea are My New Favourite
            </div>
            <div class="journal-column-date">
                By admin | March 25th, 2019
            </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'Journal'
}
</script>

<style>
    .journal-container{
        width: 62%;
        margin: 0 auto;
        position: relative;
        top: -80px;
        background-color: white;
    }
    .journal-container{
        content: "";
        display: table;
        clear: both;
    }
    .journal-title-container{
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    .journal-title{
        text-align: center;
        font-size: 20px;
        line-height: 80px;
    }
    .dotted-line{
        border-top: 1px dotted grey;
        width: 35%;
    }
    .journal-column{
        width: calc(100%/3 - 40px);
        height: calc(100% - 80px);
        float: left;
        margin-left: 30px;
    }
    .journal-img img{
        width: 100%;
        height: 100%;
    }
    .journal-column-title{
        text-align: center;
        font-size: 20px;
        margin-top: 10px;
        line-height: 30px;
    }
    .journal-column-date{
        margin: 10px 0 40px;
        text-align: center;
        font-size: 15px;
        color: grey;
    }
</style>
