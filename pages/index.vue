<template>
  <div class="home-head">
    <div class="row">
      <div class="col-md-3 col-lg-2"></div>
      <div class="col-md-9 col-lg-10">
        <div id="home-section" class="head-slider">
          <div class="intro-form" data-aos="fade-up" data-aos-delay="1500" data-aos-duration="1000">
            <div class="home-slider-img">
              <div class="slider-overlay">
                <!-- <div
                  class="home-slider-social-overlay"
                  data-aos="fade-up"
                  data-aos-delay="300"
                  data-aos-duration="1000"
                >
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

                <div class="slider-caption">
                  <h1 class="slider-title animated fadeInUp delay-1s slow">نحن نبني حلمك</h1>
                  <p
                    class="slider-desc"
                  >يهتم الاتحاد بأنماط الحياة العصرية الراقية لذا صمم لك مجموعات عقارية بمختلف الديكورات والتشطيبات والتي يتم تسليمها لك في الوقت المحدد كما نتابع معك في خدمات ما بعد البيع لنتأكد من رضائك عن الجودة العامة ومساعدتك في أي مشكلة قد تواجهك.</p>

                  <p
                    class="slider-desc"
                  >تمتع بأفضل الوحدات السكنية بأنظمة اقتصادية تناسب جميع الشرائح المختلفة لتختر منها ما يناسبك</p>

                  <div class="btn-links animated fadeInDown delay-2s slow">
                    <a href="#about-section" class="no-line">
                      <font-awesome-icon icon="angle-double-right" />المزيد عنا
                    </a>
                    <a rel="nofollow" href="tel:01009100206" class="no-line">
                      <font-awesome-icon icon="mobile-alt" />اتصل بنا الأن
                    </a>
                  </div>
                </div>

                <div class="intro-contact-form">
                  <h1 class="slider-title">تـواصل معنا الأن</h1>

                  <div class="container">
                    <form method="post" action="https://elithad.com/landingpage/go.php">
                      <div class="messages"></div>
                      <div class="row">
                        <div class="form-group col-md-6">
                          <input
                            id="form_name"
                            type="text"
                            name="name"
                            class="form-control"
                            placeholder="الأسم"
                            required="required"
                            data-error="Name is required."
                          />
                        </div>
                        <div class="form-group col-md-6">
                          <input
                            id="form_email"
                            type="email"
                            name="email"
                            class="form-control"
                            placeholder="البريد الألكتروني"
                            required="required"
                            data-error="Valid email is required."
                          />
                        </div>
                        <div class="form-group col-md-12">
                          <input
                            id="form_phone"
                            type="tel"
                            name="phone"
                            class="form-control"
                            placeholder="رقم الهاتف"
                            required="required"
                            data-error="Phone is required"
                          />
                        </div>

                        <!-- <div class="form-group col-md-6">
                          <select name="select" required class="custom-select form-control">
                            <option selected>اختيار الخدمة</option>
                            <option value="1">جراحات السمنة و المناظير</option>
                            <option value="2">الحلول الغير جراحية للسمنة</option>
                            <option value="3">التجميل النسائي</option>
                            <option value="4">الجراحات التجميلية</option>
                            <option value="5">اخري</option>
                          </select>
                        </div>-->
                        <div class="form-group col-md-12">
                          <textarea
                            id="form_message"
                            name="message"
                            class="form-control"
                            placeholder="الرسالة"
                            rows="4"
                            required="required"
                            data-error="Please,leave us a message."
                          ></textarea>
                        </div>
                        <div class="col-md-12 m-auto text-center">
                          <button class="btn btn-theme btn-radius">
                            <span>
                              <font-awesome-icon icon="paper-plane" />إرسال
                            </span>
                          </button>
                        </div>
                      </div>
                    </form>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div
          id="services-section"
          class="services section"
          data-aos="zoom-in-right"
          data-aos-delay="300"
          data-aos-duration="1000"
        >
          <div class="side-section-title">
            <h2>خدماتنا</h2>
          </div>
          <div class="services-slider">
            <div class="row">
              <div class="col-md-6 col-lg-4">
                <div class="service-item" v-b-modal.modal-center>
                  <div class="service-img">
                    <img class="image-100" src="https://6.top4top.net/p_1340c19lp6.png" alt />

                    <div class="name-wrap">
                      <span class="name">أنظمة اقتصادية تناسب الجميع</span>
                    </div>

                    <div class="more-wrap">
                      <span class="more">
                        المزيد عن الخدمة
                        <font-awesome-icon icon="angle-double-left" />
                      </span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-md-6 col-lg-4">
                <div class="service-item" v-b-modal.modal-center>
                  <div class="service-img">
                    <img class="image-100" src="https://elithad.com/landingpage/3.jpg" alt="https://3.top4top.net/p_1340rtkxl3.png" />

                    <div class="name-wrap">
                      <span class="name">وحدات إسكان بتصميمات فريدة ومختلفة</span>
                    </div>

                    <div class="more-wrap">
                      <span class="more">
                        المزيد عن الخدمة
                        <font-awesome-icon icon="angle-double-left" />
                      </span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-md-6 col-lg-4">
                <div class="service-item" v-b-modal.modal-center>
                  <div class="service-img">
                    <img class="image-100" src="https://5.top4top.net/p_1340vn9iq5.png" alt />

                    <div class="name-wrap">
                      <span class="name">مساحات مختلفة من الوحدات السكنية</span>
                    </div>

                    <div class="more-wrap">
                      <span class="more">
                        المزيد عن الخدمة
                        <font-awesome-icon icon="angle-double-left" />
                      </span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-md-6 col-lg-4">
                <div class="service-item" v-b-modal.modal-center>
                  <div class="service-img">
                    <img class="image-100" src="https://3.top4top.net/p_1339po66l3.jpg" alt />

                    <div class="name-wrap">
                      <span class="name">مجموعات عقارية بمختلف الديكورات</span>
                    </div>

                    <div class="more-wrap">
                      <span class="more">
                        المزيد عن الخدمة
                        <font-awesome-icon icon="angle-double-left" />
                      </span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-md-6 col-lg-4">
                <div class="service-item" v-b-modal.modal-center>
                  <div class="service-img">
                    <img class="image-100" src="https://6.top4top.net/p_1340c19lp6.png" alt />

                    <div class="name-wrap">
                      <span class="name">خدمات ما بعد البيع</span>
                    </div>

                    <div class="more-wrap">
                      <span class="more">
                        المزيد عن الخدمة
                        <font-awesome-icon icon="angle-double-left" />
                      </span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-md-6 col-lg-4">
                <div class="service-item" v-b-modal.modal-center>
                  <div class="service-img">
                    <img class="image-100" src="https://elithad.com/landingpage/2.jpg" alt="https://3.top4top.net/p_1340rtkxl3.png" />

                    <div class="name-wrap">
                      <span class="name">     نظام البناء بالمشاركة اتحاد ملاك</span>
                    </div>

                    <div class="more-wrap">
                      <span class="more">
                        المزيد عن الخدمة
                        <font-awesome-icon icon="angle-double-left" />
                      </span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="section-more btn-links text-center">
            <a href="javaScript:void(0)" class="no-line" v-b-modal.modal-center>
              <font-awesome-icon icon="hard-hat" />اعرف المزيد عن الخدمات
            </a>
          </div>
        </div>

        <div class="section-divider text-center">
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
          <img src="https://3.top4top.net/p_1339baude1.png" alt />
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
        </div>

        <div id="about-section" class="about section">
          <div class="side-section-title">
            <h2>رؤيتنا</h2>
          </div>
          <div class>
            <div class="row no-gutters">
              <div class="col-md-12 col-lg-4">
                <div
                  class="about-img"
                  data-aos="flip-right"
                  data-aos-delay="400"
                  data-aos-duration="1000"
                >
                  <img src="https://3.top4top.net/p_1341viyl52.png" alt class="image-100" />
                </div>
              </div>

              <div class="col-md-12 col-lg-8">
                <div
                  class="about-caption"
                  data-aos="flip-left"
                  data-aos-delay="800"
                  data-aos-duration="1000"
                >
                  <h2 class="about-title">رؤيتنا في الاتحاد للاستثمار والتطوير العقاري</h2>

                  <p
                    class="about-desc"
                  >أن نصبح رائدين في مجال الاستثمار والتطوير العقاري في الشرق الأوسط بأكمله وأن نكسب ونحافظ على رضا عملائنا من جميع أنحاء العالم من خلال الخبرات البشرية المتعددة التي تعمل جاهدة للخروج بأفضل جودة للوحدات السكنية وتقديم خدمات ما بعد البيع للعملاء.</p>

                  <h2 class="about-title">قيمنا</h2>
				   <li>
                    <font-awesome-icon icon="star" />   الثقه والالتزام
                  </li>
                  <li>
                    <font-awesome-icon icon="star" />التفاني في العمل والتحلي بروح الفريق
                  </li>
                 
                  <li>
                    <font-awesome-icon icon="star" />دقة التسليم في الموعد المحدد
                  </li>
                  <li>
                    <font-awesome-icon icon="star" />الإبداع والتطوير في كل خطوة لأي مشروع
                  </li>

                  <div class="btn-links about-links">
                    <a href="#contact-section" class="no-line">
                      <font-awesome-icon icon="paper-plane" />ارسل رسالة
                    </a>
                    <a rel="nofollow" href="tel:01009100206" class="no-line">
                      <font-awesome-icon icon="mobile-alt" />اتصل بنا الأن
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="section-divider text-center">
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
          <img src="https://3.top4top.net/p_1339baude1.png" alt />
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
          <font-awesome-icon icon="exclamation-triangle" />
        </div>

        <div id="contact-section"></div>
        <div
          class="contact section"
          data-aos="slide-up"
          data-aos-delay="300"
          data-aos-duration="1000"
        >
          <div class="side-section-title contact-title">
            <h2>تواصل معنا</h2>
          </div>

          <div class="contact-info text-center">
            <a
              rel="nofollow"
              target="_blank"
              href="https://www.google.com/maps/place/Royal+Towers+6+October+Egypt/@29.9708718,30.941347,17z/data=!3m1!4b1!4m5!3m4!1s0x14585658d9e69e9b:0x83c70fc195928237!8m2!3d29.9708672!4d30.9391583"
              class="no-line"
            >
              <font-awesome-icon icon="map-marker-alt" />ابراج رويال, السادس من اكتوبر, الجيزة
            </a>

            <a rel="nofollow" href="tel:029320483473" class="no-line">
              <font-awesome-icon icon="mobile-alt" />01009100206
            </a>
          </div>

          <div class="contact-form">
            <form method="post" action="https://elithad.com/landingpage/go.php" >
              <div class="messages"></div>
              <div class="row">
                <div class="form-group col-md-6">
                  <input
                    id="form_name"
                    type="text"
                    name="name"
                    class="form-control"
                    placeholder="الأسم"
                    required="required"
                    data-error="Name is required."
                  />
                </div>
                <div class="form-group col-md-6">
                  <input
                    id="form_email"
                    type="email"
                    name="email"
                    class="form-control"
                    placeholder="البريد الألكتروني"
                    required="required"
                    data-error="Valid email is required."
                  />
                </div>
                <div class="form-group col-md-12">
                  <input
                    id="form_phone"
                    type="tel"
                    name="phone"
                    class="form-control"
                    placeholder="رقم الهاتف"
                    required="required"
                    data-error="Phone is required"
                  />
                </div>

                <!-- <div class="form-group col-md-6">
                  <select name="select" required class="custom-select form-control">
                    <option selected>اختيار الخدمة</option>
                    <option value="1">جراحات السمنة و المناظير</option>
                    <option value="2">الحلول الغير جراحية للسمنة</option>
                    <option value="3">التجميل النسائي</option>
                    <option value="4">الجراحات التجميلية</option>
                    <option value="5">اخري</option>
                  </select>
                </div>-->
                <div class="form-group col-md-12">
                  <textarea
                    id="form_message"
                    name="message"
                    class="form-control"
                    placeholder="الرسالة"
                    rows="4"
                    required="required"
                    data-error="Please,leave us a message."
                  ></textarea>
                </div>
                <div class="col-md-12 m-auto text-center">
                  <button class="btn btn-theme btn-radius">
                    <span>
                      <font-awesome-icon icon="paper-plane" />إرسال
                    </span>
                  </button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

