<template>
<div>
 <div class="mt-5 ">
      <b-row class="d-none d-lg-flex">
           <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center">
         <h1> <b class="display-4">Who we Are</b> </h1>
               </div>
          </b-col>
      </b-row>
      <b-row class="d-none d-lg-flex  my-5">
      <b-col xl="5"  md="5">
        <div class="ml-5">
            <h3 class="ml-2 mt-3">We are a software development company that knows how to prioritize our client's business goals and needs. Our business model centers around understanding your vision
                   for your business endeavors. With us,you will be able to hire experienced software developers who will ensure the use of best industry practices,clear communication for
            familiarity with your vision to ensure continues delivery of the  best quality. </h3>
            <h3 class="ml-2 mt-3">  with us to see your ideas come to life in new and
           exciting ways as we always make sure that our products
          are up to date and can keep up with the latest trends.</h3>
        </div>
      </b-col>
      <b-col xl="1"  md="1"></b-col>
       <b-col xl="6"  md="6" align="center">
      <b-img
                  :src="require('@/assets/images/menu/imgb.png')"
                  alt="man image"
                />
      </b-col>
    </b-row>

    <b-row class="d-none d-lg-flex  my-5">
      <b-col xl="1"  md="1"></b-col>
      <b-col xl="5"  md="5" align="center">
          <div class="mt-5 ">
              <b-img
                  :src="require('@/assets/images/menu/vision.png')"
                  alt="man image"
                />
          </div>
          <div>
         <h1 class=" mt-1"> <b class="display-5">Vision</b> </h1>
            <h3 class="ml-2 mt-3 ">We envision in becoming a global leader in the software
            development industry through our innovative solutions
            and detail oriented approach to business that assures
            quality,satisfaction and success.</h3>
               </div>
      </b-col>
      <b-col xl="5"  md="5" align="center">
          <div class="mt-5">
              <b-img
                  :src="require('@/assets/images/menu/mission.png')"
                  alt="man image"
                />
          </div>
          <div>
         <h1 class=" mt-1"> <b class="display-5">Mission</b> </h1>
            <h3 class="ml-2 mt-3 ">We are on a mission to utilize our cost effective,client-
            centric and design focused business model in an ever
            changing technological landscape in empowering
            clientele to embrace change and to revolutionize
            technological solutions</h3>
               </div>
      </b-col>
      <b-col xl="1"  md="1"></b-col>
    </b-row>
 </div>

  <div class="mt-5 d-xl-none">
      <b-row >
           <b-col xl="12"  md="12" align="center" >
               <div>
         <h1> <b class="display-5">Who we Are</b> </h1>
               </div>
          </b-col>
      </b-row>
      <b-row>
      <b-col xl="6"  md="6" align="center">
        <div class="">
            <p class="mt-3 text-white">We are a software development company that knows how
            to prioritize our client's business goals and needs. Our
            business model centers around understanding your vision
            for your business endeavors. With us,you will be able to
            hire experienced software developers who will ensure the
            use of best industry practices,clear communication for
            familiarity with your vision to ensure continues delivery of
            the  best quality.</p>
            <p class="mt-3 text-white">collebrate with us to see your ideas come to life in new and
            exciting ways as we always make sure that our products
            are up to date and can keep up with the latest trends.</p>
        </div>
      </b-col>
      <b-col xl="6"  md="6" align="center" class="mx-5">
          <div class="mt-2">
              <b-img
                  :src="require('@/assets/images/menu/vision.png')"
                  alt="man image"
                />
          </div>
          <div>
         <h3 class=" mt-1"> <b>Vision</b> </h3>
            <h5 class="mt-3">We envision in becoming a global leader in the software
            development industry through our innovative solutions
            and detail oriented approach to business that assures
            quality,satisfaction and success.</h5>
               </div>
      </b-col>
      <b-col xl="6"  md="6" align="center" class="mx-5">
          <div class="mt-5">
              <b-img
                  :src="require('@/assets/images/menu/mission.png')"
                  alt="man image"
                />
          </div>
          <div>
         <h3 class=" mt-1"> <b>Mission</b> </h3>
            <h5 class="mt-3">We are on a mission to utilize our cost effective,client-
            centric and design focused business model in an ever
            changing technological landscape in empowering
            clientele to embrace change and to revolutionize
            technological solutions</h5>
               </div>
      </b-col>
      <b-col xl="12"  md="12" align="center">
      <b-img
                 class="my-3"
                  :src="require('@/assets/images/menu/imgb.png')"
                  alt="man image"
                  width="400px"
                />
      </b-col>
    </b-row>
 </div>
</div>
</template>

<script>
import {
  BRow, BCol, BImg,
} from 'bootstrap-vue'

export default {
  components: {
    BRow,
    BCol,
    BImg,
  },
  data() {
    return {
    }
  },

}
</script>

<style lang="scss">
</style>
