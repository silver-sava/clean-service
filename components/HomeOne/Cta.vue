<template>
  <section class="cta-section area-padding" style="background-image: url(/img/about/cta.png);">
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-sm-12 col-xs-12 cta-column">
          <div class="cta-content">
            <div class="title"><h1>We Clean <br /> You Should Relax.</h1></div>
            <div class="text">
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam quis nostrud exercitation ullamco laboris nisi ut aliquip.ex ea commodo consequat. duis aute irure dolor in reprehenderit.in voluptate velit esse cillum dolore eu fugiat nulla pariatur excepteur sint occaecat cupidatat.</p>
            </div>
            <div class="video-area">
              <div class="video-gallery">
                <div class="icon-holder">
                  <div class="icon">
                    <a class="mediabox html5lightbox" title="Cleaning Video" href="https://www.youtube.com/watch?v=Z7Rudw_iUWs"><i class="fa fa-play"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Cta",
      mounted() {
        MediaBox('.mediabox');
      }
    }
</script>

<style scoped>

</style>
