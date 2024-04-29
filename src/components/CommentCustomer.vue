<template lang="">
    <div class="main">
        <h1>Our Costumers Says</h1>
        <div class="card">
            <div class="comment">
                <div class="img">
                    <img src="../../public/me.jpg" alt="">
                </div>
                <div class="name">JethaLal Gada</div>
                <div class="detail">
                    <i class="bi bi-quote i-left"></i>
                    <div class="description">Love my new Apple Airpods! It's sleek, packed with features, and has great battery life. Highly recommend!</div>
                    <i class="bi bi-quote i-right"></i>
                </div>
            </div>
            <div class="comment right">
                <div class="img">
                    <img src="../../public/me.jpg" alt="">
                </div>
                <div class="name">JethaLal Gada</div>
                <div class="detail">
                    <i class="bi bi-quote i-left"></i>
                    <div class="description">Love my new Apple Airpods! It's sleek, packed with features, and has great battery life. Highly recommend!</div>
                    <i class="bi bi-quote i-right"></i>
                </div>
            </div>
            <div class="comment left">
                <div class="img">
                    <img src="../../public/me.jpg" alt="">
                </div>
                <div class="name">JethaLal Gada</div>
                <div class="detail">
                    <i class="bi bi-quote i-left"></i>
                    <div class="description">Love my new Apple Airpods! It's sleek, packed with features, and has great battery life. Highly recommend!</div>
                    <i class="bi bi-quote i-right"></i>
                </div>
            </div>
            <div class="chevron-right"><i class="bi bi-chevron-right"></i></div>
            <div class="chevron-left"><i class="bi bi-chevron-left"></i></div>
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
            text-align: center;
            margin: auto;
            font-size: 36px;
            font-weight: 800;
            margin-bottom: 24px;
        }

        .comment{
            padding: 44px 82px 44px 82px;
            margin: auto;
            width: 762px;
            /* height: 337px; */
            border-radius: 12px;
            background: #F6F6F6;
            box-shadow: 0 2px 4px #00000025;

            .img{
                margin: auto;
                width: 100px;
                height: 100px;
                border-radius: 50px;
                overflow: hidden;
                margin-bottom: 20px;

                img{
                    width: 100%;
                    height: 100%;
                }
            }

            .name{
                font-size: 24px;
                font-weight: 600;
                text-align: center;
            }

            .detail{
                text-align: center;
                position: relative;
                padding: 20px;
                font-size: 18px;

                i{
                    font-size: 24px
                }

                .i-left{
                    position: absolute;
                    top: 0;
                    left: 0;
                }

                .i-right{
                    position: absolute;
                    bottom: 0;
                    right: 0;
                    transform: rotate(180deg);
                }
            }
        }

        .card{
            position: relative;
        }

        .right{
            position: absolute;
            right: 0;
            top: 50%;
            transform: translate( 0 , -50%);
        }

        .left{
            position: absolute;
            left: 0;
            top: 50%;
            transform: translate( 0 , -50%);
        }

        .right , .left{
            width: 530px;
            padding: 50px 40px 50px 40px;
            filter: blur(2px);
            z-index: -10;
            
            .detail{
                padding: 15px;
            }

            .img{
                margin: auto;
                width: 70px;
                height: 70px;
                border-radius: 50px;
                overflow: hidden;
                margin-bottom: 15px;

                img{
                    width: 100%;
                    height: 100%;
                }
            }
        }

        .chevron-right{
            width: 70px;
            height: 70px;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #BBDEFB;
            border-radius: 50%;
            position: absolute;
            top: 50%;
            transform: translate(0 ,-50%);
            right: 85px;
            font-size: 30px;
        }

        .chevron-left{
            width: 70px;
            height: 70px;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #BBDEFB;
            border-radius: 50%;
            position: absolute;
            top: 50%;
            transform: translate(0 ,-50%);
            left: 85px;
            font-size: 30px;
        }
    }
</style>