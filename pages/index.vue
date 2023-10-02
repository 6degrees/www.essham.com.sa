<template>
  <div id="HomePage" class="alqabas">
    <Slider />
    <AboutUs />
    <Services />
    <Partners />
    <Contact />
  </div>
</template>

<script>
import Slider from '~/components/Slider.vue'
import AboutUs from '~/components/AboutUs.vue'
import Services from '~/components/Services.vue'
import Partners from '~/components/Partners.vue'
import Contact from '~/components/Contact.vue'

export default {
  name: 'IndexPage',
  components: { Slider, AboutUs, Services, Partners, Contact },
  head() {
    return {
      title: "مؤسسة إسهام لإدارة الأملاك",
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'مؤسسة إسهام تقدم حلول متكاملة لإدارة الأملاك المشتركة في المباني السكنية'
        },
        {
          hid: 'Keywords',
          name: 'Keywords',
          content: 'مباني سكنية، إدارة مرافق سكنية، خدمات الإدارة والدعم، خدمات صيانة، خدمات نظافة'
        }
      ]
    }
  }
}
</script>
