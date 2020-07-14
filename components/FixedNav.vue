<template>
  <div class="fixed-navbar" data-aos="zoom-in-left" data-aos-delay="1000" data-aos-duration="1000">
    <div class="logo">
      <img src="https://1.top4top.net/p_1339k8e7z1.png" alt />
    </div>

    <div class="navbar-btn btn-links" v-on:click="toggleNav">
      <span>
        <font-awesome-icon icon="align-right" />القائمة
      </span>
    </div>

    <div class="nav-links btn-links">
      <li>
        <a href="#home-section" class="no-line">
          <font-awesome-icon icon="home" />الرئيسية
        </a>
      </li>

      <li>
        <a href="#services-section" class="no-line navbar-btn">
          <font-awesome-icon icon="cogs" />خدماتنا
        </a>
      </li>

      <li>
        <a href="#about-section" class="no-line">
          <font-awesome-icon icon="angle-double-right" />رؤيتنا
        </a>
      </li>

      <li>
        <a href="#contact-section" class="no-line">
          <font-awesome-icon icon="paper-plane" />تواصل معنا
        </a>
      </li>

      <li>
        <a href="javaScript:void(0)" class="no-line" v-b-modal.modal-center>
          <font-awesome-icon icon="paper-plane" />ارسل رسالة
        </a>
      </li>

      <li>
        <a rel="nofollow" href="tel:01009100206" class="no-line">
          <font-awesome-icon icon="mobile-alt" />اتصل بنا الأن
        </a>
      </li>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    toggleNav: function() {
      document.querySelector(".navbar").classList.toggle("none");
    }
  }
};
</script>
