<template>
  <div class="body-wrapper">
    <Banner class="markbox bottom" />
    <main>
        <Content />
    </main>
    <Footer />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import Footer from '../components/Footer.vue'

export default {
    components: { Banner, Footer },
}
</script>