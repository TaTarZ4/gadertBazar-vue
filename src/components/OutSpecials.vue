<template lang="">
    <div class="main">
        <div class="tittle">Our Specials</div>
        <div class="list">
            <li class="item-1">
                <div class="img1">
                    <img src="../../public/item1.png" alt="">
                    <div class="price">$ 130</div>
                </div>
                <div class="text">Experience unparalleled wireless freedom with AirPods – your perfect companion for immersive sound, seamless connectivity, and all-day comfort.</div>
                <button>More Information<span><i class="bi bi-chevron-right"></i></span></button>
            </li>
            <li class="item-2">
                <div class="img2">
                    <img src="../../public/item2.png" alt="">
                    <div class="price">$ 140</div>
                </div>
            </li>
            <li class="item-3">
                <div class="img3">
                    <img src="../../public/item3.png" alt="">
                    <div class="price">$ 140</div>
                </div>
            </li>
        </div>
    </div>
</template>
<script setup>

</script>
<style scoped>
    .main{
        width: 1228px;
        margin: 76px auto 76px auto;
        .tittle{
            font-size: 36px;
            font-weight: 800;
            text-align: center;
            margin-bottom: 52px;
        }
        .list{
            list-style: none;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 1rem;
            justify-content: center;
            .img1{
                position: relative;
                width: 268px;
                height: 309px;
                overflow: hidden;
                display: flex;
                justify-content: center;
                align-items: center;
                .price{
                    position: absolute;
                    top: 20px;
                    right: 26px;
                }
                img{
                    border-radius: 12px;
                    width: 100%;
                    height: 100%;
                }
            }
            .img2{
                position: relative;
                width: 380px;
                height: 558px;
                overflow: hidden;
                display: flex;
                justify-content: center;
                align-items: center;
                .price{
                    position: absolute;
                    top: 20px;
                    right: 26px;
                }
                img{
                    border-radius: 12px;
                    width: 100%;
                    height: 100%;
                }
            }
            .img3{
                position: relative;
                width: 247px;
                height: 272px;
                overflow: hidden;
                display: flex;
                justify-content: center;
                align-items: center;
                .price{
                    position: absolute;
                    top: 20px;
                    right: 26px;
                }
                img{
                    border-radius: 12px;
                    width: 100%;
                    height: 100%;
                }
            }
            .text{
                font-size: 18px;
                margin: 39px 0 39px;
            }
            button{
                padding: 13px 19px 13px 19px;
                background-color: #3498DB;
                border-radius: 9px;
                border: none;
                color: #fff;
                span{
                    margin: 3px;
                }
            }
            .item-2{
                display: flex;
                justify-content: center;
                align-items: center;
            }
            .item-3{
                display: flex;
                flex-direction: column;
                justify-content: end;
                align-items: end;
            }
        }
    }
</style>