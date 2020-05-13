<template>
  <div class="testimonial-area area-padding">
    <div class="test-overly"></div>
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="section-headline text-center">
            <h3>Testimonial</h3>
            <p>The world's Latest at clean cleaning service company we can clean your residential space including homes.</p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="Reviews-content">

            <!-- start testimonial carousel -->
              <div class="testimonial-carousel item-indicator">
                <swiper :options="swiperOptions">
                <swiper-slide>
                <div class="single-testi text-center">
                  <div class="testi-img ">
                    <img src="img/review/1.jpg" alt="">
                  </div>
                  <div class="client-rating">
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                  </div>
                  <div class="testi-text">
                    <p>There are many variations of passages of Lorem Ipsum available, words which don't look even slightly believable.</p>
                    <h4>Arnold russel</h4>
                    <span class="guest-rev"><a href="#">Genarel customer</a></span>
                  </div>
                </div>
                </swiper-slide>
                <!-- End single item -->
                <swiper-slide>
                <div class="single-testi text-center">
                  <div class="testi-img ">
                    <img src="img/review/2.jpg" alt="">
                  </div>
                  <div class="client-rating">
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                  </div>
                  <div class="testi-text">
                    <p>There are many variations of passages of Lorem Ipsum available, words which don't look even slightly believable.</p>
                    <h4>Selena gomaz</h4>
                    <span class="guest-rev"><a href="#">Genarel customer</a></span>
                  </div>
                </div>
                </swiper-slide>
                <!-- End single item -->
                <swiper-slide>
                <div class="single-testi text-center">
                  <div class="testi-img">
                    <img src="img/review/3.jpg" alt="">
                  </div>
                  <div class="client-rating">
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                  </div>
                  <div class="testi-text">
                    <p>There are many variations of passages of Lorem Ipsum available, words which don't look even slightly believable.</p>

                    <h4>Mickhel mick</h4>
                    <span class="guest-rev"><a href="#">Genarel customer</a></span>
                  </div>
                </div>
                </swiper-slide>
                <!-- End single item -->
                <swiper-slide>
                <div class="single-testi text-center">
                  <div class="testi-img">
                    <img src="img/review/4.jpg" alt="">
                  </div>
                  <div class="client-rating">
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                    <a href="#"><i class="icon icon-star"></i></a>
                  </div>
                  <div class="testi-text">
                    <p>There are many variations of passages of Lorem Ipsum available, words which don't look even slightly believable.</p>

                    <h4>Manila meri</h4>
                    <span class="guest-rev"><a href="#">Genarel customer</a></span>
                  </div>
                </div>
                </swiper-slide>
                <!-- End single item -->
                </swiper>
              </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import { Swiper, SwiperSlide, directive } from 'vue-awesome-swiper'
  import 'swiper/css/swiper.css'
  export default {
        name: "Testimonials",
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
          slidesPerView : 3,
          loop: true,
          speed: 2000,
          spaceBetween : 20,
          autoplay: {
            delay: 3000,
            disableOnInteraction: false
          },
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          },

          // Responsive breakpoints
          breakpoints: {
            1024:{
              slidesPerView : 3
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
