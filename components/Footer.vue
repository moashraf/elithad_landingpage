<template>
  <div class="row">
    <div class="col-md-3 col-lg-2"></div>
    <div class="col-md-9 col-lg-10">
      <footer class="section">
        <div class="row">
          <div class="col-md-12 col-lg-4">
            <div class="footer-about footer-div">
              <div class="logo">
                <img src="https://1.top4top.net/p_1339k8e7z1.png" alt />
              </div>
              <p class="footer-about-p">
			  مشاريع سكنية وإدارية وتجارية   وترفيهية يقدمها لك الاتحاد بتصاميم إبداعية ومبتكرة غير مسبوقة تجربة مختلفة واستثنائية في الاتحاد للاستثمار والتطوير العقاري مع أحدث الأساليب المتبعة في التخطيط والتصميم والتنفيذ والإدارة لتحصل على ما تريد بأفضل جودة ممكنة.
			  </p>
            </div>
          </div>

          <div class="col-md-12 col-lg-4">
            <div class="footer-link btn-links footer-div">
              <div class="side-section-title footer-title">
                <h2>روابط</h2>
              </div>
              <a href="#services-section" class="no-line navbar-btn">
                <font-awesome-icon icon="cogs" />خدماتنا
              </a>

              <a href="tel:01009100206" class="no-line">
                <font-awesome-icon icon="mobile-alt" />اتصل بنا الأن
              </a>

              <a href="javaScript:void(0)" class="no-line" v-b-modal.modal-center>
                <font-awesome-icon icon="paper-plane" />ارسل رسالة
              </a>

              <a href="tel:01009100206" class="no-line">
                <font-awesome-icon icon="mobile-alt" />01009100206
              </a>
 
            </div>
          </div>

          <div class="col-md-12 col-lg-4">
            <div class="footer-follow footer-div">
              <div class="side-section-title footer-title">
                <h2>تابعنا</h2>
              </div>

              <form id="contact-form" method="post" action="https://elithad.com/landingpage/go.php">
                <input
                  id="form_email"
                  type="email"
                  name="email"
                  class="form-control"
                  placeholder="البريد الألكتروني"
                  required="required"
                  data-error="Valid email is required."
                />

                <button class="btn btn-theme btn-radius">
                  <span>
                    <font-awesome-icon icon="paper-plane" />إرسال
                  </span>
                </button>
              </form>

              <!-- <div class="home-slider-social-overlay footer-social">
                <a rel="nofollow" target="_blank" href="#" class="no-line">
                  <font-awesome-icon :icon="['fab','facebook-f']" />
                </a>

                <a rel="nofollow" target="_blank" href="#" class="no-line">
                  <font-awesome-icon :icon="['fab','twitter']" />
                </a>

                <a rel="nofollow" target="_blank" href="#" class="no-line">
                  <font-awesome-icon :icon="['fab','instagram']" />
                </a>

                <a rel="nofollow" target="_blank" href="#" class="no-line">
                  <font-awesome-icon :icon="['fab','youtube']" />
                </a>
              </div>-->
            </div>
          </div>
        </div>

        <div class="copyrights text-center">
          <p>
            <a style=" font-size: 15px;" class="no-line" target="_blank" href="https://corddigital.com/en">Cord Digital</a>
            Elithad All Rights Reserved ©2019 | By
          </p>
        </div>
      </footer>
 

<!-- GetButton.io widget -->
<script type="text/javascript">
    (function () {
        var options = {
            whatsapp: "0201009100206", // WhatsApp number
            call_to_action: "Message us", // Call to action
            position: "left", // Position may be 'right' or 'left'
        };
        var proto = document.location.protocol, host = "getbutton.io", url = proto + "//static." + host;
        var s = document.createElement('script'); s.type = 'text/javascript'; s.async = true; s.src = url + '/widget-send-button/js/init.js';
        s.onload = function () { WhWidgetSendButton.init(host, proto, options); };
        var x = document.getElementsByTagName('script')[0]; x.parentNode.insertBefore(s, x);
    })();
</script>
<!-- /GetButton.io widget -->


    </div>
  </div>
</template>
