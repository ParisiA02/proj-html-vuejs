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
          <li v-for="social,i in socials" :key="i">
            <i :class='social'></i>
          </li>
        </ul>
      </div>
    </div>
    <div class="header-logo">
      <img src="../assets/avada-food-logo.png" alt="logo">
    </div>
    <div class="header-menu">
      <ul>
        <li v-for="link,i in links" :key="i">
          {{link}}
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props:{
    links: Array,
    socials: Array
  }
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
