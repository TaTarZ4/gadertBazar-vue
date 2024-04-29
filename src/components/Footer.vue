<template lang="">
    <div class="main">
        <div class="menu">
            <div class="contact">
                <h1>Contact Us</h1>
                <div class="list">
                    <div class="location">
                        <i class="bi bi-geo-alt-fill"></i>
                        <span class="text">Naya Gaun, Pokhara-15, PKR 33700</span>
                    </div>
                    <div class="phon">
                        <i class="bi bi-telephone-fill"></i>
                        <span class="text">+977 9806771233</span>
                    </div>
                    <div class="mail">
                        <i class="bi bi-envelope-fill"></i>
                        <span class="text">bazaratgadget2234@gmail.com</span>
                    </div>
                </div>
            </div>
            <div class="quick-link">
                <h1>Quick Links</h1>
                <div class="list">
                    <div class="text">Home</div>
                    <div class="text">About</div>
                    <div class="text">Product</div>
                    <div class="text">Contact</div>
                </div>
            </div>
            <div class="social-customer">
                <div class="social">
                    <h1>Social Handles</h1>
                    <div class="icon">
                        <i class="bi bi-instagram"></i>
                        <i class="bi bi-twitter-x"></i>
                        <i class="bi bi-facebook"></i>
                    </div>
                </div>
                <div class="customer">
                    <h1>Customer Service</h1>
                    <div class="list">
                        <div class="text">Terms of Use</div>
                        <div class="text">FQA</div>
                        <div class="text">Report Issues</div>
                    </div>
                </div>
            </div>
            <div class="subscribe">
                <h1>Subscribe to our News Letter</h1>
                <div class="text">Sign up to be the first to receive latest news about our products.</div>
                <div class="input">
                    <input type="text" class="enter-email" placeholder="Enter Your Email Address">
                </div>
                <button>Subscribe <i class="bi bi-chevron-right"></i></button>
            </div>
        </div>
        <div class="footer">
            <div class="text">@2024 GadgetBazar. Shop With Us</div>
        </div>
    </div>
</template>
<script setup>

</script>
<style scoped>
    h1{
        font-size: 24px;
        font-weight: 700;
        margin-bottom: 30px;
        white-space: nowrap;
    }

    .menu{
        width: 1228px;
        margin: 120px auto 40px auto;
        display: flex;
        justify-content: space-between;
        gap: 90px;

        .text{
            font-size: 16px;
        }

        .contact i{
            margin-right: 26px;
        }

        .list{
            display: flex;
            flex-direction: column;
            gap: 5px;
        }
        
        .icon{
            display: flex;
            gap: 17px;
            font-size: 25px;
        }

        .input{
            border: solid 1px #D9D9D9;
            width: 100%;
            border-radius: 12px;
            margin: 20px 0 20px;
        }
        
        input{
            margin: 12px auto 12px 20px;
            border: none;
            outline: none;
        }

        .customer{
            margin-top: 60px;
        }

        button{
            color: #fff;
            padding: 13px 15px 13px 15px;
            background: #3498DB;
            border: none;
            border-radius: 8px;
        }
    }

    .footer{
        font-size: 16px;
        color: #fff;
        background: #3498DB;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 76px;
    }
</style>