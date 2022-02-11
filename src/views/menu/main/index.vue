<template>
<div>
 <div class="d-none d-lg-flex">
    <b-row class="match-height">
      <b-col xl="6"  md="6">
        <div class="ml-5">
      <h1> <b class="display-3 ml-2">Innovative, effective </b> </h1>
      <h1> <b class="display-3 ml-2">with quality </b> </h1>
      <h1> <b class="display-3 ml-2">assured</b> </h1>

      <h2 class="ml-2 mt-3">VoxiTec, with our talented,experienced team of developers and highly R&D team,is the best software development company to give your vision that spark of life. Our client centric,cost-effective and design focused business model will guarantee in providing exceptional results in that priorities your vision over our convenience.</h2>
      <b-button class="ml-2 mt-3"
      size="lg"
      variant="primary">
        <div class="mx-3">Get Started</div>
      </b-button>
        </div>
      </b-col>
       <b-col xl="6"  md="6">
      <b-img
                  :src="require('@/assets/images/menu/group.png')"
                  alt="main image"
                />
      </b-col>
    </b-row>
 </div>
  <div class="d-xl-none">
    <b-row class="match-height">
      <b-col xl="6"  md="6">
      <h1> <b class="display-5 mt-n5 d-flex justify-content-center">Innovative, effective </b> </h1>
      <h1> <b class="display-5 mt-n2 d-flex justify-content-center">with quality </b> </h1>
      <h1> <b class="display-5 d-flex justify-content-center">assured</b> </h1>
      </b-col>
       <b-col xl="6"  md="6">
      <b-img
                  :src="require('@/assets/images/menu/group.png')"
                  alt="main image"
                  class="ml-3 mt-3"
                />
      </b-col>
      <b-col xl="6"  md="6" align="center" class="mx-5">
      <h5 class="ml-2 mt-3">VoxiTec, with our talented,experienced team of developers and highly R&D team,is
      the best software development company to give your
      vision that spark of life. Our client centric,cost-
      effective and design focused business model will
      in providing exceptional results that
      priorities your vision over our convenience.</h5>
      </b-col>
    </b-row>
 </div>
</div>
</template>

<script>
import {
  BRow, BCol, BButton, BImg,
} from 'bootstrap-vue'

export default {
  components: {
    BRow,
    BCol,
    BButton,
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
