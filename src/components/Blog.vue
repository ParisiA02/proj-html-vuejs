<template>
<div class="blog-container">
    <div class="blog-title title">
        FARM TO TABLE
    </div>
    <button class="btn blog-btn">
        READ OUR BLOG
    </button>
    <div class="blog-subtitle subtitle">
        Aliquam erat volutpat. Ut quis ligua a magna vlandit finibus. Spendisse maximus lacus non nunc lacinia lobortis.
    </div>
    <div class="blog-column-container">
        <div class="blog-column column-left">
            <img src="../assets/single-post-img3-1200x790.jpg" alt="resturant-pic">
            <div class="column-left-title">
                Food Corner: Top Japanese Restaurants for Sushi
            </div>
            <div class="column-left-subtitle">
                By admin | March 25th, 2019
            </div>
            <div class="dotted-line">
            </div>
            <div class="column-left-text">
                Suspendisse at semper odio. Nam fringilla scelerisque tincidunt. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec tincidunt posuere ornare. Phasellus placerat odio non feugiat sollicitudin. Integer vitae elementum ex.
            </div>
            <span> Read More ></span>
        </div>
        <div class="blog-column column-right">
            <div class="upper-image">
                <div class="text-container">
                    VIEW OUR LATEST RECIPES
                </div>
            </div>
            <div class="down-image">
                <div class="text-container">
                    City Guide: Singapore
                </div>
            </div>
            <div class="btn down-img-btn">
                VIEW ALL CITY GUIDES
            </div>
            <div class="line"></div>
        </div>
    </div>
    <div class="blod-down-column-container">
        <div class="blog-image-container">
            <div class="blog-image-card">
                <div class="blog-img">
                    <img src="../assets/fi-roundup-400x263.jpg" alt="resturant-img">
                </div>
                <div class="blog-column-title">
                    Roundup: My New Favourite Recipes For Healty Living
                </div>
                <div class="blog-column-date">
                    By admin | March 25th, 2019
                </div>
            </div>
            <div class="blog-image-card">
                <div class="blog-img">
                    <img src="../assets/fi-korean-food-400x263.jpg" alt="resturant-img">
                </div>
                <div class="blog-column-title">
                    Meal Prep: Koren Bibimbap with Kimichi
                </div>
                <div class="blog-column-date">
                    By admin | March 25th, 2019
                </div>
            </div>
            <div class="blog-image-card">
                <div class="blog-img">
                    <img src="../assets/fi-toasts-400x263.jpg" alt="resturant-img">
                </div>
                <div class="blog-column-title">
                    Why These Toasts with Tea are My New Favorite
                </div>
                <div class="blog-column-date">
                    By admin | March 25th, 2019
                </div>
            </div>
            <div class="blog-image-card">
                <div class="blog-img">
                    <img src="../assets/fi-street-food-400x263.jpg" alt="resturant-img">
                </div>
                <div class="blog-column-title">
                    Exploring Street Food in Bangkok
                </div>
                <div class="blog-column-date">
                    By admin | March 25th, 2019
                </div>
            </div>
            <div class="blog-image-card">
                <div class="blog-img">
                    <img src="../assets/fi-organic-breakfast-400x263.jpg" alt="resturant-img">
                </div>
                <div class="blog-column-title">
                    Organic Choices For Healthier Living
                </div>
                <div class="blog-column-date">
                    By admin | March 25th, 2019
                </div>
            </div>
            <div class="blog-image-card">
                <div class="blog-img">
                    <img src="../assets/fi-water-side-rest-400x263.jpg" alt="resturant-img">
                </div>
                <div class="blog-column-title">
                    5 Waterside Restaurants in Istanbul for Special Events
                </div>
                <div class="blog-column-date">
                    By admin | March 25th, 2019
                </div>
            </div>
            <button class="btn more-post-btn">
                LOAD MORE POSTS
            </button>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'Blog'
}
</script>

<style lang="scss">
    .blog-container{
        width: 62%;
        margin: 0 auto;

        .blog-title{
            margin-top: 200px;
            text-align: left;
            display: inline-block;
        }
        .blog-subtitle{
            text-align: left;
            line-height: 30px;
            margin-left: 0;
            margin-bottom: 70px;
        }
        .blog-btn{
            float: right;
            margin-top: 185px;
        }

        .blog-column-container{
            width: 100%;
            display: flex;
            justify-content: space-between;

            .blog-column{
                height: 100%;

                img{
                    width: 100%;
                }

                .column-left-text{
                    line-height: 30px;
                }

                .dotted-line{
                    width: auto;
                    margin: 20px 30px 20px 30px;
                }

            }
            .blog-column.column-left{
                width: 65%;
                background-color: white;
            }
            .blog-column.column-left span{
                display: inline-block;
                margin: 30px 0 40px 30px;
                color: grey;
                font-size: 15px;
            }
            .blog-column.column-right .upper-image{
                width: 350px;
                height: 420px;
                background-image: url("../assets/latest-recipe.jpg");
                background-position: center;
                background-size: cover;
                display: flex;
                justify-content: center;
                align-items: center;

                .text-container{
                    font-size: 20px;
                    line-height: 30px;
                    width: 30%;
                    text-align: center;
                    color: #333338;
                }
            }

            .blog-column.column-right .down-image{
                width: 350px;
                height: 230px;
                margin-top: 50px;
                background-image: url("../assets/singapore-featured-image.jpg");
                background-position: center;
                background-size: cover;
                
                .text-container{
                    width: 70%;
                    height: 50px;
                    font-size: 20px;
                    text-align: center;
                    vertical-align: middle;
                    line-height: 50px;
                    color: white;
                    position: relative;
                    top: 135px;
                    background-color: rgba(0, 0, 0, 0.8);
                }
            }
            .down-img-btn{
                text-align: center;
                height: 40px;
                line-height: 10px;
            }
            .line{
                width: 100%;
                float: right;
                border-bottom: 1px solid lightgrey;
                margin-top: 50px;
            }
        }
        .blod-down-column-container{
            width: 100%;
            background-color: red;
            
            .blog-image-container{
                width: 65%;
                margin-top: 50px;
                display: flex;
                flex-wrap: wrap;
                justify-content: space-between;

                .blog-image-card{
                    width: calc(100%/2 - 20px);
                    margin-bottom: 40px;
                    background-color: white;
                }
                .blog-img img{
                    width: 100%;
                    height: 100%;
                }
                .blog-column-title{
                    width: 80%;
                    margin: 0 auto;
                    text-align: center;
                    font-size: 20px;
                    margin-top: 10px;
                    line-height: 30px;
                }
                .blog-column-date{
                    margin: 10px 0 30px;
                    text-align: center;
                    font-size: 15px;
                    color: grey;
                }
                .more-post-btn{
                    width: 100%;
                    color: #333338;
                    background-color: lightgrey;
                }
            }
        }
    }
</style>
