<template>
  <div class="project-area area-padding">
    <div class="">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="section-headline text-center">
            <h3>Our Projects</h3>
            <p>The world's Latest at clean cleaning service company we can clean your residential space including homes.</p>
          </div>
        </div>
      </div>
        <div class="row">
          <div class="col-lg-12 col-md-12">
            <div class="shorting-menu">
              <button class="filter" data-filter="all">All</button>
              <button class="filter" data-filter=".residential">Residential</button>
              <button class="filter" data-filter=".commercial ">Commercial</button>
              <button class="filter" data-filter=".apartment">Apartment</button>
            </div>
          </div>
        </div>

      <div class="project-content" >
        <div class="row m-0">
          <!-- single-awesome-project start -->
          <div class="col-lg-4 col-md-6 mix residential p-0 ">
            <div class="single-work">
              <img src="/img/project/1.jpg" alt="work-img">

              <div class="work-content">
                <h4>Cleaning</h4>
                <ul>
                  <li><a href="#">Residential</a></li>
                  <li>.</li>
                  <li><a href="#">Service</a></li>
                </ul>
              </div>

              <a href="/img/project/1.jpg" class="popup-btn"><i class="fa fa-plus"></i></a>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="col-lg-4 col-md-6 mix commercial p-0">
            <div class="single-work">
              <img src="/img/project/2.jpg" alt="work-img">

              <div class="work-content">
                <h4>Cleaning</h4>
                <ul>
                  <li><a href="#">Commercial</a></li>
                  <li>.</li>
                  <li><a href="#">Service</a></li>
                </ul>
              </div>

              <a href="/img/project/2.jpg" class="popup-btn"><i class="fa fa-plus"></i></a>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="col-lg-4 col-md-6 mix apartment p-0">
            <div class="single-work">
              <img src="/img/project/3.jpg" alt="work-img">

              <div class="work-content">
                <h4>Cleaning</h4>
                <ul>
                  <li><a href="#">Apartment</a></li>
                  <li>.</li>
                  <li><a href="#">Service</a></li>
                </ul>
              </div>

              <a href="/img/project/3.jpg" class="popup-btn"><i class="fa fa-plus"></i></a>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="col-lg-4 col-md-6 mix commercial p-0">
            <div class="single-work">
              <img src="/img/project/4.jpg" alt="work-img">

              <div class="work-content">
                <h4>Cleaning</h4>
                <ul>
                  <li><a href="#">Home</a></li>
                  <li>.</li>
                  <li><a href="#">Service</a></li>
                </ul>
              </div>

              <a href="/img/project/4.jpg" class="popup-btn"><i class="fa fa-plus"></i></a>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="col-lg-4 col-md-6 mix residential p-0">
            <div class="single-work">
              <img src="/img/project/5.jpg" alt="work-img">

              <div class="work-content">
                <h4>Cleaning</h4>
                <ul>
                  <li><a href="#">Carpet</a></li>
                  <li>.</li>
                  <li><a href="#">Service</a></li>
                </ul>
              </div>

              <a href="/img/project/5.jpg" class="popup-btn"><i class="fa fa-plus"></i></a>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="col-lg-4 col-md-6 mix apartment p-0">
            <div class="single-work">
              <img src="/img/project/6.jpg" alt="work-img">

              <div class="work-content">
                <h4>Cleaning</h4>
                <ul>
                  <li><a href="#">Garden</a></li>
                  <li>.</li>
                  <li><a href="#">Service</a></li>
                </ul>
              </div>

              <a href="/img/project/6.jpg" class="popup-btn"><i class="fa fa-plus"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End main content -->
  </div>
</template>

<script>
    export default {
        name: "Project",
      mounted(){
        var containerEl = document.querySelector('.project-content');
        var mixer = mixitup(containerEl);
      }



    }
</script>

<style scoped>
  .project-menu li a {
    text-decoration: none !important;
  }

</style>
