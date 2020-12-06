<template>
  <div class="home">
    <HeaderSection />
    <HeroSection />   
    <BannerSection /> 
    <GallerySection /> 
    <PartnerLogoSection /> 
    <FooterSection /> 
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSection from '@/components/HeaderSection.vue'
import HeroSection from '@/components/HeroSection.vue'
import BannerSection from '@/components/BannerSection.vue'
import GallerySection from '@/components/GallerySection.vue'
import PartnerLogoSection from '@/components/PartnerLogoSection.vue'
import FooterSection from '@/components/FooterSection.vue'

export default {
  name: 'Home',
  components: {
    HeaderSection, 
    HeroSection, 
    BannerSection, 
    GallerySection,
    PartnerLogoSection,
    FooterSection,
  }
}
</script>
