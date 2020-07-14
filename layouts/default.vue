<template>
  <div>
    <FixedNav />
    <Popup />
    <transition name="slide-fade">
      <nuxt />
    </transition>
    <Footer />
    <Form />
  </div>
</template>

<script>
import FixedNav from "~/components/FixedNav.vue";
import Footer from "~/components/Footer.vue";
import Form from "~/components/Form.vue";
import Popup from "~/components/Popup.vue";

export default {
  components: {
    FixedNav,
    Footer,
    Form,
    Popup
  }
};
</script>
