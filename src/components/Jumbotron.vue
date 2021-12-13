<template>
  <div class="container">
    <div class="event-tab">
        <div class="todays-pick">
            TODAY'S PICK
        </div>
        <div class="event-tab-text">
            Food Corner: Top Japanese Restaurants for Sushi
        </div>
        <div class="event-tab-date">
            March 25, 2019
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Jumbotron'
}
</script>

<style>

    .container{
        width: 100%;
        height: 700px;
        background-image: url("../assets/single-post-img3.jpg");
        background-size: cover;
        background-position: center;
        padding: 170px;
        
    }
    .todays-pick{
        width: 155px;
        height: 40px;
        text-align: center;
        line-height: 40px;
        border-radius: 10px;
        margin: 0 auto;
        font-weight: bold;
        color: white;
        background-color: #fa7423;
        position: relative;
        top: -20px;
    }
    .event-tab{
        width: 700px;
        height: 230px;
        margin: 0 auto;
        border-radius: 10px;
        background-color: white;
    }
    .event-tab-text{
        font-size: 40px;
        text-align: center;
        padding-top: 30px;
    }
    .event-tab-date{
        text-align: center;
        margin-top: 20px;
    }
</style>
