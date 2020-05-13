<template>

  <div class="counter-area area-padding parallax-bg" data-stellar-background-ratio="0.6">
    <div class="container">
      <div class="row">
        <div v-observe-visibility="onVisibilityChange" class="col-md-12 col-sm-12 col-xs-12">
          <div class="col-md-12 col-sm-12">

            <div class="about-count">

              <div class="fun-content">
                <div class="fun_text">
                  <a href="#"><i class="icon icon-diamond"></i></a>
                  <span class="counter">
                    <countTo :startVal='0' :endVal='startCounter ? 9400 : 0' :duration='3000'></countTo>
                  </span>
                  <h5>Complete Projects</h5>
                </div>
                <!-- fun_text  -->
                <div class="fun_text">
                  <a href="#"><i class="icon icon-star"></i></a>
                  <span class="counter">
                    <countTo :startVal='0' :endVal='startCounter ? 5250 : 0' :duration='3000'></countTo>
                  </span>
                  <h5>Happy Clients</h5>
                </div>
                <!-- fun_text  -->
                <div class="fun_text">
                  <a href="#"><i class="icon icon-layers"></i></a>
                  <span class="counter">
                    <countTo :startVal='0' :endVal='startCounter ? 179 : 0' :duration='3000'></countTo>
                  </span>
                  <h5>Present Projects</h5>
                </div>
                <!-- fun_text  -->
                <div class="fun_text">
                  <a href="#"><i class="icon icon-users"></i></a>
                  <span class="counter">
                    <countTo :startVal='0' :endVal='startCounter ? 2184 : 0' :duration='3000'></countTo>
                  </span>
                  <h5>Total Employee</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import countTo from 'vue-count-to';
  import { ObserveVisibility } from 'vue-observe-visibility'
    export default {
        name: "Counter",
      components: { countTo },
      directives: {
        ObserveVisibility
      },
      data() {
        return{
          startCounter: false
        }
      },
      methods: {
        onVisibilityChange (isVisible) {
          if (isVisible){
            this.startCounter = true;
          }

        },
      },
    }
</script>

<style scoped>

</style>
