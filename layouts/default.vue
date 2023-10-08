<template>
  <div>
    <AppHeader />
    <Nuxt />
    <a style="color: inherit;" href="https://api.whatsapp.com/send?phone=+966548064886&text=ارغب في الاستفسار"
      class="layer_999 float d-flex align-items-center justify-content-center" target="_blank" aria-label="WhatsApp Chat with Support">
      <i class="bi text-white bi-whatsapp my-float"></i>
    </a>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from '~/components/inc/AppHeader.vue';
import AppFooter from '~/components/inc/AppFooter.vue';

export default {
  name: 'default',
  components: {
    AppHeader,
    AppFooter,
  }
}
</script>

<style>
.float {
  position: fixed;
  z-index: 999;
  width: 60px;
  height: 60px;
  bottom: 40px;
  right: 40px;
  background-color: #25d366;
  color: #FFF;
  border-radius: 50px;
  text-align: center;
  font-size: 30px;
  box-shadow: 2px 2px 3px #999;
  text-decoration: none;
}
</style>