<template lang="">
    <div class="main">
        <h1>Best Sellers</h1>
        <p>Discover our curated collection of best sellers – handpicked favorites loved by our customers for their exceptional quality, performance, and value.</p>
        <div class="list">
            <div class="item">
                <img src="../../public/best1.png" alt="">
                <div class="tittle">
                    <div class="name">Smart Watch</div>
                    <div class="price">$ 300</div>
                </div>
            </div>
            <div class="item">
                <img src="../../public/best2.png" alt="">
                <div class="tittle">
                    <div class="name">Head Phone</div>
                    <div class="price">$ 300</div>
                </div>
            </div>
            <div class="item">
                <img src="../../public/best3.png" alt="">
                <div class="tittle">
                    <div class="name">Digital Camera</div>
                    <div class="price">$ 300</div>
                </div>
            </div>
        </div>
        <div class="shop-here">
            <button>Shop Hero <span><i class="bi bi-chevron-right"></i></span></button>
        </div>
        <div class="best-item">
            <div class="text">
                <div class="tittle">Get your next must-have Gadget</div>
                <div class="description">Collect the innovation you love. Explore our curated selection of high-tech wonders, designed to elevate your daily life and inspire your passions.</div>
                <button>Buy Now <span><i class="bi bi-chevron-right"></i></span></button>
            </div>
            <div class="img">
                <img src="../../public/img2.png" alt="">
                <img src="../../public/best4.png" alt="" class="img-item">
            </div>
        </div>
        <div class="best-item">
            <div class="img">
                <img src="../../public/img2.png" alt="">
                <img src="../../public/best5.png" alt="" class="img-item">
            </div>
            <div class="text">
                <div class="tittle">Discover exclusive offers</div>
                <div class="description">Take advantage of our limited-time offers and enjoy discounts of up to [Percentage] off. Don't miss out – shop now and elevate your tech game today!</div>
                <button>Buy Now <span><i class="bi bi-chevron-right"></i></span></button>
            </div>
        </div>
    </div>
</template>
<script setup>

</script>
<style scoped>
    .main{
        width: 1228px;
        margin: auto;
        
        h1{
            font-size: 36px;
            font-weight: 800;
            text-align: center;
        }

        p{
            font-size: 18px;
            margin: 27px auto 52px auto;
            width: 785px;
            text-align: center;
        }

        .list{
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 44px;

            .item{
                position: relative;
                border-radius: 15px;
                overflow: hidden;
                display: flex;
                justify-content: center;
                align-items: end;
                width: 380px;
                height: 527px;

                img{
                    position: absolute;
                    width: 100%;
                    height: 100%;
                    z-index: -10;
                }

                .tittle{
                    display: flex;
                    align-items: center;
                    justify-content: space-between;
                    padding: 27px 24px 27px 24px;
                    width: 100%;
                    background: #00000029;
                    color: #fff;
                    font-weight: 600;
                }
            }
        }
        .shop-here{
            display: flex;
            justify-content: center;

            button{
                padding: 13px 17px 13px 17px;
                margin: 52px auto 52px auto;
                border: none;
                border-radius: 8px;
                background: #3498DB;
                color: #fff;
            }
        }

        .best-item{
            margin: 76px 0 76px 0;
            display: flex;
            justify-content: space-between;

            .tittle{
                font-size: 64px;
                font-weight: 800;
            }
            
            .description{
                font-size: 20px;
                margin: 27px 0 27px 0;
            }

            button{
                padding: 13px 15px 13px 15px;
                border: none;
                border-radius: 8px;
                color: #fff;
                background: #3498DB;
            }

            .img{
                position: relative;
            }

            .img-item{
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-60% , -50%);
            }
        }
    }
</style>