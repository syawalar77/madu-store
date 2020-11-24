<template>
    <section class="intro">
        <div class="intro-middle-left text-white">
            <!-- <Title title="Produk Kami"/> -->
            <h1>Selamat Datang di Website Kami</h1>
            <p>Pelayanan Penjualan Madu Secara Online. Terbukti, Terpercaya dan Berkualitas. Untuk Pemesanan Silahkan Klik di Bawah Ini</p>
            <!-- <button type="submit" class="btn btn-warning text-white"><b>BELI SEKARANG</b></button> -->
            <a  
                href="https://wa.me/6281398110834"
                target="_blank"
            >
                <Button 
                    titleBtn="BELI SEKARANG"
                    class="button-intro"
                />
            </a>
        </div>
        <div class="intro-middle-right">
            <img src="~/assets/image/honey2.jpg" style="width: 450px; height: 400px;" alt="not found" class="image">
        </div>
        
    </section>
   
</template>

<script>
import Title from '~/components/atoms/Title.vue'
import Button from '~/components/atoms/Button.vue'

export default {
    Title: Title,
    Button: Button,
}
</script>

<style>
    .intro{
        margin-top: 60px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: #ffc107;
        padding: 100px 0px 60px;
        max-width: 100%;
       
    }
    .intro-middle-left{
        width: 530px;
    }
    .intro-middle-left h1{
        font-weight: bold;
    }
    .intro-middle-left p{
        font-weight: bold;
    }
    .intro-middle-right .image{
        border-top-left-radius: 50%;
        border-bottom-right-radius: 20%;
        border-top-right-radius: 8px;
        border-bottom-left-radius: 8px;
        object-fit: cover;
    }
    .button-intro {
        border:1px solid white;
        width: 142px;
        text-align: center;
        border-radius: 5px;
    }
    @media(max-width: 600px) {
        .intro-middle-right .image {
            width: 100% !important;
            height: 300px;
            padding: 50px;
        }
        .intro-middle-left {
            width: 100%;
            padding: 0 16px;
            text-align: center;
        }
        .button-intro {
            text-align: center;
            margin-left: 30%;
        }
        .intro{
            margin-top: 20px;
            max-width: 100%;
            display: block;
        }
    }

    /* }
    .intro-middle-left{
        Height: 197px;
        Top: 171px;
        font-weight: 650;
        font-style: normal;
        font-size: 25px;
        line-height: 36px;
        color: white;
        color: black;
    }
    .intro-middle-left p{
        width: 403px;
    }
    .intro-middle-right{
        width: 377px;    
        Height: 362.22px;
        Top: 117.77px;
    }
    .intro-middle-button{
        width: 141px;
        height: 39.05px;
        background: #A4DEF9;
        font-size: 18px;
        border: 1px solid #FFFFFF;
        box-sizing: border-box;
        color: white;
    }
    @media(max-width: 992px) {
        .intro {
            max-width: 100% !important;
            display: block;
            justify-content: center;
            align-items: center;
            padding: 50px 100px 82px 100px;
            margin-top: 50px;
        }
        .intro-middle-right {
            padding-top: 50px;
        }
    } */
</style>