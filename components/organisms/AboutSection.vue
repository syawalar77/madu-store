<template>
    <section class="about" id="about">
        <div class="title-section">
            <h3 class="title-about">Tentang Kami</h3>
            <p class="about-content">Lorem ipsum dolor, sit amet consectetur adipisicing elit. In atque suscipit fugiat ea ullam, omnis officiis quas delectus blanditiis nihil doloribus impedit eaque obcaecati labore, velit, provident ipsum consectetur tempore.</p>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" allowfullscreen></iframe>
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
.about {
    width: 100%;
    padding: 80px;
    background-color: #f4f4f2;
}
.title-section .title-about {
    font-weight: bold;
    font-size: 40px;
}
.title-about::after {
    content: "";
    display: block;
    width: 150px;
    height: 2px;
    margin: 24px auto;
    background: #ffc107;
}
.row {
    text-align: center;
}
.title-section {
    text-align: center;
    margin: 0px auto;
}
p.about-content {
    text-align: center;
    padding-bottom: 50px;
    font-size: 22px;
  padding: 0px 140px;

    
}
iframe {
    width: 70%;
    height: 400px;
    border-radius: 10px;
    border: transparent;
    box-shadow: 0px 0px 55px #ffc107;
}
@media(max-width: 768px) {
    .about{
        width: 100%;
        margin: 50px auto 0px;
        padding: 0px;
    }
    .title-section .about-content {
        width: 100%;
        margin: 0px auto;
        padding: 0px 10px 10px 10px;
        font-size: 17px;
        display: none;
                
    }
    .container .row .col{
        padding: 0px;
        margin: 0px;
        width: 100%;
        
    }
    iframe{
        width: 70%;
        height: 180px;

    }
}
</style>