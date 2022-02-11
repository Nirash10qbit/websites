<template>
<div class="bg">
 <div class="mt-5 ">
      <b-row class="d-none d-lg-flex">
           <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center my-5">
         <h1> <b class="display-4">Blogs</b> </h1>
               </div>
          </b-col>
      </b-row>
 </div>

  <div class="mt-5 d-xl-none">
      <b-row >
          <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center mt-4 mb-3">
                   <h2> <b>Blogs</b> </h2>
                </div>
          </b-col>
      </b-row>
 </div>
 <b-row >
        <b-col xl="1"  md="1">
        </b-col>
        <b-col xl="10"  md="10">
            <b-row>
                <b-col sm="6" xl="4"  md="4" align="center" class="match-height mb-2">
                    <div class="mx-5">
                  <b-card bg-variant="white" class="rounded-card match-height">
                      <b-img
                  :src="require('@/assets/images/menu/blog/p1.png')"
                  alt="man image"
                />
                          <div>
         <h3 class="mt-1 text-dark">13 October, 2021</h3>
         <h2 class="mt-1 text-dark"><b>Top 15 Data Mining Tools To Discover Patterns And Correlations</b></h2>
         <h3 class="mt-1 text-dark"> Data analytics and informatics are seen to be having enormous potential to meet the challenges of today’s organizations. Data is...</h3>
               </div>
                  </b-card>
                    </div>
              </b-col>
                 <b-col sm="6" xl="4"  md="4" align="center" class="match-height mb-2">
                    <div class="mx-5">
                  <b-card bg-variant="white" class="rounded-card match-height">
                      <b-img
                  :src="require('@/assets/images/menu/blog/p2.png')"
                  alt="man image"
                />
                          <div>
         <h3 class="mt-1 text-dark">13 October, 2021</h3>
         <h2 class="mt-1 text-dark"><b>Top 15 Data Mining Tools To Discover Patterns And Correlations</b></h2>
         <h3 class="mt-1 text-dark"> Data analytics and informatics are seen to be having enormous potential to meet the challenges of today’s organizations. Data is...</h3>
               </div>
                  </b-card>
                    </div>
              </b-col>
                 <b-col sm="6" xl="4"  md="4" align="center" class="match-height mb-2">
                    <div class="mx-5">
                  <b-card bg-variant="white" class="rounded-card match-height">
                      <b-img
                  :src="require('@/assets/images/menu/blog/p3.png')"
                  alt="man image"
                />
                          <div>
         <h3 class="mt-1 text-dark">13 October, 2021</h3>
         <h2 class="mt-1 text-dark"><b>Top 15 Data Mining Tools To Discover Patterns And Correlations</b></h2>
         <h3 class="mt-1 text-dark"> Data analytics and informatics are seen to be having enormous potential to meet the challenges of today’s organizations. Data is...</h3>
               </div>
                  </b-card>
                    </div>
              </b-col>
            </b-row>
        </b-col>
        <b-col xl="1"  md="1">
        </b-col>
  </b-row>
  <div class="d-flex justify-content-center my-5">
     <b-button
         class="rounded-pill mb-3"
        v-ripple.400="'rgba(255, 255, 255, 1)'"
        variant="secondary"
        >
         Read more
        </b-button>
     </div>
</div>
</template>

<script>
import {
  BRow, BCol, BImg, BCard, BButton,
} from 'bootstrap-vue'

export default {
  components: {
    BRow,
    BCol,
    BImg,
    BCard,
    BButton,
  },
  data() {
    return {
    }
  },

}
</script>

<style>
.rounded-card{
    border-radius:50px;
}
.bg{
    background-color: #121212;
}
</style>
