<template>
  <div class="home">
    <app-home-intro></app-home-intro>
    <app-home-featured></app-home-featured>
    <app-home-features></app-home-features>
    <app-home-work></app-home-work>
  </div>
</template>

<script>
// import AppHomeBottomBanner from '../components/home/AppHomeBottomBanner.vue'
// import AppHomeCount from '../components/home/AppHomeCount.vue'
import AppHomeFeatured from '../components/home/AppHomeFeatured.vue'
import AppHomeFeatures from '../components/home/AppHomeFeatures.vue'
import AppHomeIntro from '../components/home/AppHomeIntro.vue'
import AppHomeWork from '../components/home/AppHomeWork.vue'
// import AppHomeNews from '../components/home/AppHomeNews.vue'
// import AppHomePartners from '../components/home/AppHomePartners.vue'
// import AppHomeTestominials from '../components/home/AppHomeTestominials.vue'
// import AppHomeValues from '../components/home/AppHomeValues.vue'
// import AppHomeWork from '../components/home/AppHomeWork.vue'

export default {
  name: 'Home',
  components: {
    AppHomeIntro,
    AppHomeFeatured,
    AppHomeFeatures,
    AppHomeWork
  }
}
</script>
<style>
  
</style>