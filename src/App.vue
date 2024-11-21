<template>
  <div class="flex flex-col items-center max-w-xl mx-auto bg-white">
    <HeroSection />
    <AboutCampaign />
    <Products />
    <Gallery />
    <PriceTable />
    <YoutubeEmbed />
    <Testimonials />
    <OrderingProcess />
    <FAQ />
    <Contact />
    <MetaPixel />
  </div>
</template>

<script>
import HeroSection from './components/HeroSection.vue'
import AboutCampaign from './components/AboutCampaign.vue'
import Products from './components/Products.vue'
import Gallery from './components/Gallery.vue'
import Testimonials from './components/Testimonials.vue'
import PriceTable from './components/PriceTable.vue'
import OrderingProcess from './components/OrderingProcess.vue'
import Contact from './components/Contact.vue'
import YoutubeEmbed from './components/YoutubeEmbed.vue'
import FAQ from './components/FAQ.vue'
import MetaPixel from './components/MetaPixel.vue'

export default {
  components: {
    HeroSection,
    AboutCampaign,
    Products,
    Gallery,
    Testimonials,
    PriceTable,
    OrderingProcess,
    Contact,
    YoutubeEmbed,
    FAQ,
    MetaPixel,
  },
}
</script>

<style>
/* Tambahan gaya global jika perlu */
</style>