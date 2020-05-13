<template>
  <div class="project-area project-column-2 area-padding">
    <div class="">
      <div class="row">
        <!-- Start Portfolio -page -->
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
        <div class="project-content container">
          <!-- single-awesome-project start -->
          <div class="project-single all-padding commercial mix">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a class="venobox" data-gall="myGallery" href="img/project/1.jpg">
                  <img src="img/project/1.jpg" alt="" />
                  <div class="add-actions text-center">
                    <div class="project-dec">
                      <h4>Nice project</h4>
                      <span>Commercial</span>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="project-single all-padding residential mix">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a class="venobox" data-gall="myGallery" href="img/project/2.jpg">
                  <img src="img/project/2.jpg" alt="" />
                  <div class="add-actions text-center">
                    <div class="project-dec">
                      <h4>Nice project</h4>
                      <span>Residential</span>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="project-single all-padding residential mix">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a class="venobox" data-gall="myGallery" href="img/project/3.jpg">
                  <img src="img/project/3.jpg" alt="" />
                  <div class="add-actions text-center">
                    <div class="project-dec">
                      <h4>Nice project</h4>
                      <span>Residential</span>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="project-single all-padding apartment mix">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a class="venobox" data-gall="myGallery" href="img/project/4.jpg">
                  <img src="img/project/4.jpg" alt="" />
                  <div class="add-actions text-center">
                    <div class="project-dec">
                      <h4>Nice project</h4>
                      <span>Apartment</span>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="project-single all-padding commercial mix">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a class="venobox" data-gall="myGallery" href="img/project/5.jpg">
                  <img src="img/project/5.jpg" alt="" />
                  <div class="add-actions text-center">
                    <div class="project-dec">
                      <h4>Nice project</h4>
                      <span>commercial</span>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- single-awesome-project end -->
          <!-- single-awesome-project start -->
          <div class="project-single all-padding apartment mix">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a class="venobox" data-gall="myGallery" href="img/project/6.jpg">
                  <img src="img/project/6.jpg" alt="" />
                  <div class="add-actions text-center">
                    <div class="project-dec">
                      <h4>Nice project</h4>
                      <span>Apartment</span>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <!-- single-awesome-project end -->
        </div>
      </div>
    </div>
    <!-- End main content -->
  </div>
</template>

<script>
    export default {
        name: "ProjectTwo",
      mounted(){
        var containerEl = document.querySelector('.project-content');
        var mixer = mixitup(containerEl);
      },

    }
</script>

<style scoped>
  .project-menu li a {
    text-decoration: none !important;
  }
</style>
