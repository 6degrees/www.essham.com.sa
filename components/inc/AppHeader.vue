<template>
  <div class="alqabas">
    <nav class="navbar navbar-expand-lg shadow" :class="navbarClass" id="navbarTag">
      <div class="container">
        <a class="navbar-brand" href="/#homepage">
          <img src="@/static/images/EsshamLogo.png" class="logo-img" alt="Eshaam Logo">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
          aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav ms-auto navbar-nav-center">
            <li class="nav-item">
              <a class="nav-link" href="/#ContactUs">تواصل معنا</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/#Services">خدماتنا</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/#AboutUs">من نحن</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/#HomePage">الرئيسية</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  data() {
    return {
      isScrolled: false,
    };
  },
  computed: {
    navbarClass() {
      return {
        'fixed-top': this.isScrolled
      };
    },
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.handleScroll);
  },
  methods: {
    handleScroll() {
      if (window.scrollY > 0) {
        this.isScrolled = true;
      } else {
        this.isScrolled = false;
      }
    },
  },
};
</script>

<style scoped>
.logo-img {
  width: 140px;
}
</style>