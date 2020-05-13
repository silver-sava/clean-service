<template>
  <section>
    <!-- Hero Slider Area -->
    <div class="slider-area">
      <div class="slider-on">
        <swiper :options="swiperOptions">
          <swiper-slide>
            <div class="single-slider">
              <!-- Slider Image -->
              <div class="slider-img">
                <img src="/img/slider/header.jpg" alt="header.jpg">
              </div>
              <div class="slider-text text-center">
                <!--<span class="welcome">Welcome To Demosite</span>-->
                <h2>WE ARE <span>DIGITAL CLEANING SERVICE</span> COMPANY</h2>
                <p>The world's Latest at clean cleaning service company we can clean your <br
                  class="br"> residential space including homes.</p>
                <a href="#about" class="skill-btn" data-toggle="modal" data-target="#myModal">GET A FREE QUATE</a>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div class="single-slider">
              <!-- Slider Image -->
              <div class="slider-img">
                <img src="/img/slider/header-2.jpg" alt="header2.jpg">
              </div>
              <div class="slider-text text-center">

                <h2>WE ARE <span>DIGITAL CLEANING SERVICE</span> COMPANY</h2>
                <p>The world's Latest at clean cleaning service company we can clean your<br
                  class="br"> residential space including homes.</p>
                <a href="#about" class="skill-btn" data-toggle="modal" data-target="#myModal">GET A FREE QUATE</a>
              </div>
            </div>
          </swiper-slide>
          <div class="swiper-pagination owl-dots" slot="pagination"></div>
        </swiper>
      </div>
    </div>

  </section>
</template>

<script>
  import { Swiper, SwiperSlide, directive } from 'vue-awesome-swiper'
  import 'swiper/css/swiper.css'
    export default {
        name: "SliderOne",
      components: {
        Swiper,
        SwiperSlide
      },
      directives: {
        swiper: directive
      },
      data() {
        return {
          swiperOptions: {
            slidesPerView : 1,
            loop: true,
            speed: 2000,
            spaceBetween : 20,
            autoplay: {
              delay: 3000,
              disableOnInteraction: false
            },

            pagination: {
              el: '.swiper-pagination',
              type: 'bullets',
              clickable: true
            },

            // Responsive breakpoints
            breakpoints: {
              1024:{
                slidesPerView : 1
              },
              768:{
                slidesPerView : 1
              },
              640:{
                slidesPerView : 1
              },
              320:{
                slidesPerView : 1
              }
            }
          }
        }
      },
    }
</script>

<style scoped>

</style>
