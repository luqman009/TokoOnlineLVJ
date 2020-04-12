<template>
  <div class="home">
    <HeaderToko />
    <HeroToko />
    <BannerToko />
    <InstagramToko />
    <LogoPartner />
    <FooterToko />
  </div>
</template>

<script>
// @ is an alias to /src
 import HeaderToko from '@/components/HeaderToko.vue';
 import HeroToko from '@/components/HeroToko.vue';
 import BannerToko from '@/components/BannerToko.vue';
 import InstagramToko from '@/components/InstagramToko.vue';
 import LogoPartner from '@/components/LogoPartner';
 import FooterToko from '@/components/FooterToko';

export default {
  name: 'Home',
  components: {
      HeaderToko,
      HeroToko,
      BannerToko,
      InstagramToko,
      LogoPartner,
      FooterToko,
  }
};
</script>
