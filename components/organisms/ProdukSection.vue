<template>
    <div class="our-product" id="product">
        <div class="card-product">
            <h3 class="card-title">Produk Kami</h3>
                <div class="container">
                    <div class="card-content row">
                        <div class="card" style="width: 18rem;">
                        <img src="~/assets/image/honey3.jpg" class="card-img-top" style="height: 190px" alt="...">
                        <div class="card-body">
                            <h3 class="card-title-one">Madu Kopi</h3>
                            <!-- <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis non repudiandae obcaecati sed molestias,</p> -->
                        </div>
                        </div>
                        <div class="card" style="width: 18rem;">
                            <img src="~/assets/image/honey2.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h3 class="card-title-two">Madu Hutan</h3>
                                <!-- <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Natus ea explicabo magnam nam nesciunt!</p> -->
                            </div>
                        </div>
                        <div class="card" style="width: 18rem;">
                        <img src="~/assets/image/honey.jpg" class="card-img-top" style="height: 190px;" alt="...">
                        <div class="card-body">
                            <h3 class="card-title-three">Madu Kaliandra</h3>
                            <!-- <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum eos ex numquam accusamus adipisci deserunt</p> -->
                        </div>
                    </div>
                </div>
                 <button type="submit" class="btn btn-warning text-white mt-4"><b>MUALI BELI</b></button>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .our-product{
    max-width: 100%!important;
    text-align: center;
    padding-top: 100px;
    padding-bottom: 20px;
    background-color: #f4f4f2;

}
.card-title::after {
    content: "";
    display: block;
    width: 150px;
    height: 2px;
    margin: 24px auto;
    background: #ffc107;
}
.card-content {
    display: flex;
    justify-content: center;
}
.card {
    width: 18rem!important;
    margin: 10px 6px;
    text-align: center;
    border: 1px solid #eee;
    border-radius: 8px;
    box-shadow: 0 0 4px #ffc107;
}
.card-body {
    background-color: #f4f4f2;
}
.card-title {
    height: 120px;
    font-size: 40px;
    font-weight: bold;
}
.card-title-one, .card-title-two, .card-title-three {
    font-size: 25px;
    font-weight: 700;
}

</style>