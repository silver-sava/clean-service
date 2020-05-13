<template>
  <header class="header-style-3">
    <!-- Start top bar -->
    <div class="topbar-area topbar-3 fix hidden-xs">
      <div class="container">
        <div class="row">
          <div class=" col-md-12 col-sm-12">
            <div class="topbar-left">
              <div class="quote-button">
                <a href="/order-from" class="quote-btn">Booking Service</a>
              </div>
              <ul>
                <li><a href="#"><i class="icon icon-phone"></i>+123 456 0945</a></li>
                <li><a href="#"><i class="icon icon-envelope"></i>Email clean@support.com</a></li>
                <li><a href="#"><i class="icon icon-clock"></i>8:00 Am - 5:00 Pm</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End top bar -->
    <!-- header-area start -->
    <div id="sticker" :class="`header-area header-area-3 hidden-xs ${sticky ? 'stick' : '' }`">
      <div class="container">
        <div class="row">
          <!-- logo start -->
          <div class="col-md-3 col-sm-3">
            <div class="logo">
              <!-- Brand -->
              <nuxt-link class="navbar-brand page-scroll sticky-logo" to="/">
                <img src="/img/logo/logo.png" alt="">
              </nuxt-link>
            </div>
          </div>
          <!-- logo end -->
          <div class="col-md-9 col-sm-9">
            <div class="header-right-link">
              <!-- search option start -->
              <div @click="searchToogle = !searchToogle" class="search-inner">
                <form action="#">
                  <div :style="`display: ${searchToogle ? 'block' : ''}`"   class="search-option">
                      <input type="text" placeholder="Search...">
                      <button class="button" type="submit"><i class="fa fa-search"></i></button>
                  </div>
                  <a class="main-search" href="#"><i class="fa fa-search"></i></a>
                </form>
              </div>
              <!-- search option end -->
            </div>
            <!-- mainmenu start -->
            <nav class="navbar navbar-default">
              <div class="collapse navbar-collapse" id="navbar-example">
                <div class="main-menu">
                  <ul class="nav navbar-nav navbar-right">
                    <li><a class="pagess" href="#">Home</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/">Home 01</nuxt-link></li>
                        <li><nuxt-link to="/index-2">Home 02</nuxt-link></li>
                        <li><nuxt-link to="/index-3">Home 03</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">About us</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/about">About us</nuxt-link></li>
                        <li><nuxt-link to="/team">Team</nuxt-link></li>
                        <li><nuxt-link to="/review">Review</nuxt-link></li>
                        <li><nuxt-link to="/faq">FAQ</nuxt-link></li>
                        <li><nuxt-link to="/error">Error</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Services</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/services">Services</nuxt-link></li>
                        <li><nuxt-link to="/single-service">Single Services</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Projects</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/project-4">Project 4 </nuxt-link></li>
                        <li><nuxt-link to="/project-3">Project 3 </nuxt-link></li>
                        <li><nuxt-link to="/project-2">Project 2 </nuxt-link></li>
                        <li><nuxt-link to="/single-project">Single Project</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Blog</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/blog-grid-2">Blog 2 grid</nuxt-link></li>
                        <li><nuxt-link to="/blog-grid-3">Blog 3 column</nuxt-link></li>
                        <li><nuxt-link to="/blog-grid-1">Blog Sidebar</nuxt-link></li>
                        <li><nuxt-link to="/blog-details">Blog Details</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link to="/contact">contacts</nuxt-link></li>
                  </ul>
                </div>
              </div>
            </nav>
            <!-- mainmenu end -->
          </div>
        </div>
      </div>
    </div>
    <!-- header-area end -->
    <!-- mobile-menu-area start -->
    <div class="mobile-menu-area hidden-lg hidden-md hidden-sm">
      <div class="container  mean-container">
        <div class="row">
          <div class="col-md-12">
            <div class="mobile-menu">
              <div class="logo">
                <nuxt-link to="/"><img src="img/logo/logo.png" alt="" /></nuxt-link>
              </div>
              <div class="mean-bar">
                <nav id="dropdown" class="mean-nav">
                  <a @click="mobileToogle = !mobileToogle" href="#nav" class="meanmenu-reveal menuToggle"><span></span><span></span><span></span></a>
                  <ul :style="`display: ${mobileToogle ? 'block' : 'none'}`">
                    <li><a class="pagess" href="#">Home</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/">Home 01</nuxt-link></li>
                        <li><nuxt-link to="/index-2">Home 02</nuxt-link></li>
                        <li><nuxt-link to="/index-3">Home 03</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">About us</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/about">About us</nuxt-link></li>
                        <li><nuxt-link to="/team">Team</nuxt-link></li>
                        <li><nuxt-link to="/review">Review</nuxt-link></li>
                        <li><nuxt-link to="/faq">FAQ</nuxt-link></li>
                        <li><nuxt-link to="/error">Error</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Services</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/services">Services</nuxt-link></li>
                        <li><nuxt-link to="/single-service">Single Services</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Projects</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/project-4">Project 4 </nuxt-link></li>
                        <li><nuxt-link to="/project-3">Project 3 </nuxt-link></li>
                        <li><nuxt-link to="/project-2">Project 2 </nuxt-link></li>
                        <li><nuxt-link to="/single-project">Single Project</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Blog</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/blog-grid-2">Blog 2 grid</nuxt-link></li>
                        <li><nuxt-link to="/blog-grid-3">Blog 3 column</nuxt-link></li>
                        <li><nuxt-link to="/blog-grid-1">Blog Sidebar</nuxt-link></li>
                        <li><nuxt-link to="/blog-details">Blog Details</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link to="/contact">contacts</nuxt-link></li>
                  </ul>
                </nav>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- mobile-menu-area end -->
  </header>
</template>

<script>
    export default {
        name: "HeaderOne",
      data() {
        return {
          sticky: false,
          mobileToogle : false,
          searchToogle :false,
        }
      },
      mounted() {
        window.addEventListener('scroll', this.handleScroll);

      },
      methods: {

        handleScroll(){
          if ( window.scrollY > 100 ){
            this.sticky = true
          }
          else if ( window.scrollY < 100 ) {
            this.sticky = false
          }
        },


      }
    }
</script>

<style scoped>

</style>
