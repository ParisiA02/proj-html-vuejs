<template>
  <div class="header">
    <div class="upper-header">
      <div class="left-header">
        <ul>
          <li>Dowload App</li>
          <li>Advertise with us</li>
        </ul>
      </div>
      <div class="right-header">
        <ul>
          <li><img src="../assets/image.svg" alt=""></li>
          <li><img src="../assets/image.svg" alt=""></li>
          <li><img src="../assets/image.svg" alt=""></li>
          <li><img src="../assets/image.svg" alt=""></li>
        </ul>
      </div>
    </div>
    <div class="header-logo">
      <img src="../assets/avada-food-logo.png" alt="">
    </div>
    <div class="header-menu">
      <ul>
        <li>Home</li>
        <li>Recipes</li>
        <li>Places</li>
        <li>Blog</li>
        <li>About</li>
        <li>Contact</li>
        <li><img src="../assets/image.svg" alt=""></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss">
  .header{
    height: 250px;
    background-color: white;
    
    .upper-header{
      width: 60%;
      margin: 0 auto;
      color: grey;

      .left-header ul, .right-header ul{
        list-style-type: none;
        margin-top: 20px;
        li{
          display: inline;
          padding: 10px;
        }
      }
      .left-header{
        float: left;
      }
      .right-header{
        float: right; 
      }
    }

    .header-logo{
      text-align: center;
      padding-top: 50px;
    }
    .header-menu{
      width: 40%;
      margin: 0 auto;
      padding: 20px;
      text-align: center;

      ul{
        list-style-type: none;
        li{
          display: inline;
          padding: 25px;
        }
      }
    }
  }
</style>
