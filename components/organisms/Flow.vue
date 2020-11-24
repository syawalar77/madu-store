<template>
    <section class="flowusers">
        <div class="flowusers-title">
            <h2>Flow Pelayanan User</h2>
        </div>
        <div class="flowusers-image">
            <div class="daptar" style="width: 130px; ">
                <img src="~assets/image/daptar.png" alt="not found">
                <p>Whatsaap</p>
            </div>
            <div class="negosiasi" style="width: 130px; ">
                <img src="~assets/image/Konsultasi.png" alt="not found">
                <p>Pemesanan</p>
            </div>
            <div class="pembayaran" style="width: 130px; ">
                <img src="~assets/image/pembayaran.png" alt="not found">
                <p>Pembayaran</p>
            </div>
            <div class="mentoring" style="width: 130px; ">
                <img src="~assets/image/selesai.png" alt="not found">
                <p>Selesai</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
     .flowusers {
        border-radius: 50PX;
        margin: 80px 80px;
        background-color: #ffc107;
        padding: 30px 0px;
        color: white;
    }
    .flowusers-title h2{
        text-align: center;
        font-size: 32px;
        font-weight: 700;
        padding: 20px 10px;
        
    }
    .flowusers-image {
        display: flex;
        justify-content: center;
        text-align: center;
        padding: 30px 0px;
    }

    .flowusers-image p{
        margin-top: 20px;
        font-size: 16px;
        font-weight: 700;
    }
    .flowusers-title h2::after {
        content: "";
        display: block;
        border: 1px solid white;
        text-align: center;
        width: 150px;
        margin: 10px auto 0px;
    }
    @media(max-width: 768px) {
        .flowusers{
            max-width: 100%;
            margin: 80px 20px 0px 20px;
        }
        .flowusers-image img{
            width: 50px;
        }
        .flowusers-image p{
            font-size: 9px;
    
        }
        .flowusers-title{
            max-width: 100%;
            text-align: center;
            
        }
        .flowusers-title h2{
            font-size: 40px;
            padding: 0px;
            font-weight: 700;
           
           
        }
    }

</style>