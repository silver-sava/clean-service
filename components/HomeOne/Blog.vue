<template>
  <div class="blog-area area-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="section-headline text-center">
            <h3>Latest News</h3>
            <p>The world's Latest at clean cleaning service company we can clean your residential space including homes.</p>
          </div>
        </div>
      </div>
      <div class="blog-slider">
        <swiper :options="swiperOptions">
          <swiper-slide>
            <div class="col-lg-12 col-md-12">
              <div class="single-blog">
                <div class="blog-image">
                  <a class="image-scale" href="#">
                    <img src="img/blog/3.jpg" alt="">
                  </a>
                </div>
                <div class="blog-content">
                  <div class="blog-title">
                    <div class="blog-meta">
                                            <span class="date-type">
                                                12 Dec, 2019
                                            </span>
                      <span class="comments-type">
                                                <i class="fa fa-comment-o"></i>
                                                13
                                            </span>
                    </div>
                    <a href="#">
                      <h4>Residential cleaning service</h4>
                    </a>
                  </div>
                  <div class="blog-text">
                    <p>Redug Lagre dolor sit amet, consectetur adipisicing elit. Minima in nostrum, veniam. Esse est assumenda inventore.</p>
                    <a class="blog-btn" href="#">Read more</a>
                  </div>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="col-lg-12 col-md-12">
              <div class="single-blog">
                <div class="blog-image">
                  <a class="image-scale" href="#">
                    <img src="img/blog/2.jpg" alt="">
                  </a>
                </div>
                <div class="blog-content">
                  <div class="blog-title">
                    <div class="blog-meta">
                                            <span class="date-type">
                                                14 Nov, 2019
                                            </span>
                      <span class="comments-type">
                                                <i class="fa fa-comment-o"></i>
                                                12
                                            </span>
                    </div>
                    <a href="#">
                      <h4>Carpet cleaning instrument</h4>
                    </a>
                  </div>
                  <div class="blog-text">
                    <p>Redug Lagre dolor sit amet, consectetur adipisicing elit. Minima in nostrum, veniam. Esse est assumenda inventore.</p>
                    <a class="blog-btn" href="#">Read more</a>
                  </div>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="col-lg-12 col-md-12">
              <div class="single-blog">
                <div class="blog-image">
                  <a class="image-scale" href="#">
                    <img src="img/blog/1.jpg" alt="">
                  </a>
                </div>
                <div class="blog-content">
                  <div class="blog-title">
                    <div class="blog-meta">
                                            <span class="date-type">
                                                14 Nov, 2019
                                            </span>
                      <span class="comments-type">
                                                <i class="fa fa-comment-o"></i>
                                                10
                                            </span>
                    </div>
                    <a href="#">
                      <h4>Cleaning services system</h4>
                    </a>
                  </div>
                  <div class="blog-text">
                    <p>Redug Lagre dolor sit amet, consectetur adipisicing elit. Minima in nostrum, veniam. Esse est assumenda inventore.</p>
                    <a class="blog-btn" href="#">Read more</a>
                  </div>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="col-lg-12 col-md-12">
              <div class="single-blog">
                <div class="blog-image">
                  <a class="image-scale" href="#">
                    <img src="img/blog/3.jpg" alt="">
                  </a>
                </div>
                <div class="blog-content">
                  <div class="blog-title">
                    <div class="blog-meta">
                                            <span class="date-type">
                                                14 Nov, 2019
                                            </span>
                      <span class="comments-type">
                                                <i class="fa fa-comment-o"></i>
                                                15
                                            </span>
                    </div>
                    <a href="#">
                      <h4>Carpet cleaning instrument</h4>
                    </a>
                  </div>
                  <div class="blog-text">
                    <p>Redug Lagre dolor sit amet, consectetur adipisicing elit. Minima in nostrum, veniam. Esse est assumenda inventore.</p>
                    <a class="blog-btn" href="#">Read more</a>
                  </div>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="col-lg-12 col-md-12">
              <div class="single-blog">
                <div class="blog-image">
                  <a class="image-scale" href="#">
                    <img src="img/blog/b4.jpg" alt="">
                  </a>
                </div>
                <div class="blog-content">
                  <div class="blog-title">
                    <div class="blog-meta">
                                            <span class="date-type">
                                                14 Nov, 2019
                                            </span>
                      <span class="comments-type">
                                                <i class="fa fa-comment-o"></i>
                                                18
                                            </span>
                    </div>
                    <a href="#">
                      <h4>Cleaning services system</h4>
                    </a>
                  </div>
                  <div class="blog-text">
                    <p>Redug Lagre dolor sit amet, consectetur adipisicing elit. Minima in nostrum, veniam. Esse est assumenda inventore.</p>
                    <a class="blog-btn" href="#">Read more</a>
                  </div>
                </div>
              </div>
            </div>
          </swiper-slide>
        </swiper>
      </div>
      <!-- End row -->
    </div>
  </div>
</template>

<script>
  import { Swiper, SwiperSlide, directive } from 'vue-awesome-swiper'
  import 'swiper/css/swiper.css'
    export default {
        name: "Blog",
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
            speed: 1000,
            spaceBetween : 20,
            autoplay: {
              delay: 3000,
              disableOnInteraction: false
            },

            // Responsive breakpoints
            breakpoints: {
              1024:{
                slidesPerView : 3
              },
              768:{
                slidesPerView : 2
              },
              640:{
                slidesPerView : 2
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
