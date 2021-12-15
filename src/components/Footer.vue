<template>
  <div class="general-footer">
    <div class="footer-container">
      <div class="footer-column">
        <div class="footer-logo">
          <img src="../assets/avada-food-logo-mob-2x.png" alt="footer-logo">
        </div>
        <ul class="left-column-ul">
          <li class="left-column-li" v-for="social,i in socials" :key="i">
            <i :class='social'></i>
          </li>
        </ul>
      </div>
      <div class="footer-column">
        <ul class="mid-left-column-ul">
          <li v-for="link,j in links" :key="j" class="mid-left-column-li">{{link}}</li>
        </ul>
      </div>
      <div class="footer-column">
        <span class="contact">CONTACT</span>
        <ul class="mid-right-column-ul">
          <li class="mid-right-column-li" v-for="icon,i in contacts.icon" :key="i">
            <i :class="icon"></i>
            <div class="text-container">
            <span v-for="text,k in contacts.text[i]" :key="k">{{text}}</span>
            </div>
          </li>
        </ul>
      </div>
      <div class="footer-column column-right">
        <span class="contact">GET OUR APP!</span>
        <div class="footer-column-img-cotnainer">
          <img src="../assets/download-android.png" alt="">
          <img src="../assets/download-app-store.png" alt="">
        </div>
      </div>
    </div>
    <div class="under-footer">
      <a href="#header"><span><i class="fas fa-chevron-up"></i></span></a>
      © Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered By WordPress
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props:{
    contacts: Object,
    links: Array,
    socials: Array 
  }

}
</script>

<style lang="scss">
  .general-footer{
    background-color: white;
    
    .footer-container{
      width: 65%;
      height: 400px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      
      .footer-column{
        width: calc(100%/4);
        height: 250px;
        border-right: 1px dotted grey;
  
        .footer-logo{
          text-align: center;
          img{
            width: 80%;
          }
        }
  
        .left-column-ul{
          list-style: none;
          margin-top: 40px;
          margin-left: 30px;
  
          .left-column-li{
            display: inline-block;
            margin-right: 10px;

            i{
              color: grey;
              font-size: 20px;
              margin-right: 10px;
            }
          }
        }
  
        .mid-left-column-ul{
          list-style: none;
          margin-left: 50px;
          .mid-left-column-li{
            margin-bottom: 30px;
            color: #333338;
          }
        }
  
        .contact{
          color: #FC8137;
          display: inline-block;
          margin-left: 40px;
        }
  
        .mid-right-column-ul{
          list-style: none;
          margin-left: 50px;
          margin-top: 20px;

          .mid-right-column-li{
            margin-bottom: 20px;
            line-height: 20px;
            vertical-align: center;
            color: grey;
            display: flex;
  
            i{
              margin-right: 20px;
            }
            .text-container{
              width: 100%;
            }
            span{
              display: inline-block;
              margin-right: 1px;
            }
          }
        }
  
        .footer-column-img-cotnainer{
          margin-top: 30px;
          margin-left: 40px;
  
          img{
            width: 250px;
            margin-bottom: 15px;
          }
        }
      }
      .column-right{
        border-right: none;
      }
    }
    .under-footer{
      width: 100%;
      height: 80px;
      background-color: #F5F5F1;
      text-align: center;
      line-height: 80px;
      vertical-align: middle;
      font-size: 12px;
      color: grey;

      span{
        background-color: #464646;
        padding: 20px;
        border-radius: 50%;
        position: relative; 
        right: 600px;
        cursor: pointer;
        color: white;
      }
    }
  }
</style>
