<template>
        <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="navbarSupportedContent">
            <div class="container">
                <a class="navbar-brand text-light" href="/">
                    Madustore.id
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon">
                    </span>
                </button>
                <div class="collapse  navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav  ml-auto ">
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toAboutusElement">
                            Tentang Kami
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toProductElement">
                            Produk
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toExcellenceElement">
                            Keunggulan
                        </a></li>
                        <li class="nav-item"><a class="nav-link text-light mr-4" @click="toTestimoniElement">
                            Testimoni
                        </a></li>
                    </div>
                </div>
            </div>
        </nav>
</template>

<script>
export default {
    data() {
        return {
            aboutusElement: "",
            productElement: "",
            excellenceElement: "",
            testimoniElement: "",
        };
    },
    mounted() {
        this.aboutusElement = document.getElementById("about");
        this.productElement = document.getElementById("product");
        this.excellenceElement = document.getElementById("excellence");
        this.testimoniElement = document.getElementById("testimoni");
},
    methods: {
        hideMenu() {
            let menuContainer = document.getElementById('navbarNavAltMarkup')
            menuContainer.classList.remove("show")
        },
        toAboutusElement() {
            this.aboutusElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
        toProductElement() {
            this.productElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()
        },
        toExcellenceElement() {
            this.excellenceElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()  
        },
        toTestimoniElement() {
            this.testimoniElement.scrollIntoView({
                behavior: "smooth",
                block: "start",
                inline: "nearest",
            });
            this.hideMenu()  
        },
    },
};
</script>

<style>
.navbar {
    background-color: #ffc107;
}

.navbar-dark .navbar-nav .nav-link {
    cursor: pointer!important;
    font-size: 20px;
    font-weight: 700;
}
.navbar-dark .navbar-brand {
    font-size: 22px;
    font-weight: bold;
}
</style>