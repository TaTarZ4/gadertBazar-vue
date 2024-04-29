<template lang="">
    <div class="main">
        <div class="list">
            <li>
                <div class="icon">
                    <i class="bi bi-truck"></i>
                </div>
                <div class="text">Offering expedited shipping options and ensuring timely delivery of orders, with tracking information available for customers.</div>
            </li>
            <li>
                <div class="icon">
                    <i class="bi bi-wechat"></i>
                </div>
                <div class="text">Providing multiple channels for customer support, including live chat, email, and phone support, to address any queries or issues promptly.</div>
            </li>
            <li>
                <div class="icon">
                    <i class="bi bi-tags"></i>
                </div>
                <div class="text">Offering discounts, coupons, and promotional offers to incentivize purchases and reward loyal customers.</div>
            </li>
            <li>
                <div class="icon">
                    <i class="bi bi-coin"></i>
                </div>
                <div class="text">Providing a hassle-free return policy and easy refund process for customers in case they are not satisfied with their purchases.</div>
            </li>
        </div>
    </div>
</template>
<script setup>

</script>
<style scoped>
    
    .main{
        background-image: url("../../public/img4.png");
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .list{
        width: 1228px;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        gap: 45px;
        margin: 75px auto 75px auto;

        li{
            border-radius: 12px;
            padding: 25px;
            list-style: none;
            background: #BBDEFB;
            .icon{
                width: 60px;
                height: 60px;
                background: #3498DB;
                border-radius: 9px;
                display: flex;
                justify-content: center;
                align-items: center;
                margin-bottom: 30px;
                i{
                    font-size: 31px;
                    color: white;
                }
            }
            .text{
                font-size: 16px;
            }
        }
    }
</style>