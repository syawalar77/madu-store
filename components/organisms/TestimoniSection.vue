<template>
    <section class="testimoni" id="testimoni">
        <div class="container">
            <div class="row">
                <div class="col testimoni-title">
                    <h3>Apa Kata Mereka Tentang Produk Kami?</h3>
                </div>
            </div>
            <div class="row">
                <div class="col-md-4 sm-6">
                    <div class="testimoni-card">
                        <img class="rounded-circle" src="~/assets/image/boy.png" alt="not found">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis nam facilis et quidem, perferendis quos exercitationem. 
                            Quas qui neque facilis laboriosam architecto cumque? Nobis quas eveniet ipsa dolorum magnam itaque dolore ab commodi animi, 
                            temporibus nam accusamus a! Odit vel consequuntur sequi similique, laborum, 
                            illum libero sed totam error ullam molestiae ipsa in eligendi laudantium deleniti 
                            </p>
                        <div><b>RAHMAN</b><span> - PENGACARA</span></div>
                    </div>
                </div>
                <div class="col-md-4 sm-6">
                    <div class="testimoni-card">
                        <img class="rounded-circle" src="~/assets/image/girl.png" alt="not found">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis nam facilis et quidem, perferendis quos exercitationem. 
                            Quas qui neque facilis laboriosam architecto cumque? Nobis quas eveniet ipsa dolorum magnam itaque dolore ab commodi animi, 
                            temporibus nam accusamus a! Odit vel consequuntur sequi similique, laborum, 
                            illum libero sed totam error ullam molestiae ipsa in eligendi laudantium deleniti 
                            </p>
                        <div><b>ZAHRA</b><span> - DOKTER</span></div>
                    </div>

                </div>
                <div class="col-md-4 sm-6">
                    <div class="testimoni-card">
                        <img class="rounded-circle" src="~/assets/image/man.png" alt="not found">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis nam facilis et quidem, perferendis quos exercitationem. 
                            Quas qui neque facilis laboriosam architecto cumque? Nobis quas eveniet ipsa dolorum magnam itaque dolore ab commodi animi, 
                            temporibus nam accusamus a! Odit vel consequuntur sequi similique, laborum, 
                            illum libero sed totam error ullam molestiae ipsa in eligendi laudantium deleniti 
                            </p>
                        <div><b>MADAN</b><span> - PENGUSAHA</span></div>
                    </div>
                </div>
            </div>


        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
    .testimoni{
        margin-top: 70px;
        padding-bottom: 80px;
        text-align: center;
        background-color: white;
    }
    .testimoni-title{
        padding: 20px 0px;
        color: #303030;
    }
    .testimoni-title h3{
        font-size: 40px;
        font-weight: bold;
    }
    .testimoni-title h3::after{
        content: ''; 
        display: block;
        color: #f56607;
        border: 1px solid #f56607;
        width: 150px;
        text-align: center;
        margin: 15px auto;
    }
    .testimoni-card{
        border: 1px solid #eaeaea;
        padding: 10px 30px;
        line-height: 30px;
        background: rgba(215, 231, 215, 0.1);  
        box-shadow: 8px 10px 10px #eaeaea;  
    }
    .testimoni-card img{
        padding: 10px 10px;
        border: 2px dashed #e65c00;
        border-radius: 50%;
    }
    .testimoni p{
        color: rgb(83, 79, 79);
    }
    @media (max-width: 768px) {
        .testimoni-card {
            margin-top: 20px;
        }
    }
</style>