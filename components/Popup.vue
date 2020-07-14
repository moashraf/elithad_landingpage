<template>
  <div class="navbar none" v-on:click="hideNav">
    <div class="navbar-wrap text-center">
      <div class="navbar-links btn-links">
        <li>
          <a href="#home-section" class="no-line">
            <font-awesome-icon icon="home" />الرئيسية
          </a>
        </li>

        <li>
          <a href="#services-section" class="no-line">
            <font-awesome-icon icon="cogs" />الخدمات
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

        <!-- <div class="popup-social">
          <a rel="nofollow" target="_blank" href="#" class="no-line">
            <font-awesome-icon :icon="['fab', 'facebook-f']" />
          </a>

          <a rel="nofollow" target="_blank" href="#" class="no-line">
            <font-awesome-icon :icon="['fab', 'twitter']" />
          </a>

          <a rel="nofollow" target="_blank" href="#" class="no-line">
            <font-awesome-icon :icon="['fab', 'instagram']" />
          </a>

          <a rel="nofollow" target="_blank" href="#" class="no-line">
            <font-awesome-icon :icon="['fab', 'youtube']" />
          </a>
        </div>-->
      </div>
    </div>

    <div class="close-navbar btn-links">
      <span>
        <font-awesome-icon icon="times" />اغلاق
      </span>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    hideNav: function() {
      document.querySelector(".navbar").classList.toggle("none");
    }
  }
};
</script>
