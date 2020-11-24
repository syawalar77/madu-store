<template>
  <div>
    <Navbar/>
    <Intro/>
    <About/>
    <Produk/>
    <Benefit/>
    <Flow/>
    <Testimoni/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from "~/components/organisms/NavbarSection.vue"
import Intro from "~/components/organisms/Intro.vue"
import About from "~/components/organisms/AboutSection.vue"
import Produk from "~/components/organisms/ProdukSection.vue"
import Benefit from "~/components/organisms/BenefitSection.vue"
import Flow from "~/components/organisms/Flow.vue"
import Testimoni from "~/components/organisms/TestimoniSection.vue"
import Footer from "~/components/organisms/Footer.vue"

export default {
  components: {
    Navbar,
    Intro,
    About,
    Produk,
    Benefit,
    Flow,
    Testimoni,
    Footer,
  }
}
</script>

<style>

</style>
