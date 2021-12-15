<template>
    <div class="subscribe-and-image-container">
        <div class="subscribe-container">
            <div class="subscribe-title">Subscine & Receive A Free eBook</div>
            <div class="subscribe-subtitle">
                Aliquam erat volutpat. Ut quis ligula a magna blandit finibus. Suspensdisse masximus lacus non nunc lacinia
            </div>
            <div class="search-bar-container">
                <input type="search" placeholder="insert your email...">
                <button>Subscribe</button>
            </div>
            <div class="subscribe-text">
                Cras porttior pellentesque sem eu pretium.
            </div>
        </div>
        <div class="subscribe-img-container">
            <div class="subscribe-img">
                <img src="../assets/Yogurt-Nan-600x395.jpg" alt="">
            </div>
            <div class="subscribe-img">
                <img src="../assets/Mixed-fruits-600x395.jpg" alt="">
            </div>
            <div class="subscribe-img">
                <img src="../assets/r-rachel-park-366508-unsplash-min-600x395.jpg" alt="">
            </div>
            <div class="subscribe-img">
                <img src="../assets/r-michelle-tsang-500721-unsplash-min-600x395.jpg" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Subscribe'
}
</script>

<style lang="scss">
    .subscribe-container{
        width: 100%;
        height: 500px;
        background-image: url("../assets/subscribe-sec-bg.png");
        background-position: center;
        background-size: cover;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;

        .subscribe-title{
            font-size: 30px;
            color: #333338;
        }
        .subscribe-subtitle{
            font-size: 15px;
            margin: 30px 0;
            color: #333338;
        }

        input{
            width: 500px;
            height: 50px;
            font-size: 15px;
            padding-left: 20px;
            margin-right: 30px;
        }
        button{
            height: 50px;
            width: 200px;
            font-size: 20px;
            color: white;
            background-color: #FC7523;
            border: none;
        }
        .subscribe-text{
            margin-top: 40px;
            color: grey;
        }
    }
    .subscribe-img-container{
        width: 100%;
        display: flex;
        .subscribe-img{
            width: calc(100%/4);
            img{
                width: 100%;
                display: block;
            }
        }
    }
</style>
