<template>
<div>
 <div class="mt-5 ">
      <b-row class="d-none d-lg-flex">
           <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center my-5">
         <h1> <b class="display-4">Technologies we work with</b> </h1>
               </div>
          </b-col>
      </b-row>
 </div>

  <div class="mt-5 d-xl-none">
      <b-row >
          <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center mt-4">
                   <h2> <b>Technologies we work</b> </h2>
                </div>
          </b-col>
           <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center">
                   <h2> <b>with</b> </h2>
                </div>
          </b-col>
      </b-row>
 </div>
  <b-row >
          <b-col xl="1"  md="1" >
          </b-col>
           <b-col xl="10"  md="10" >
               <div class="mt-3 mb-3 d-flex justify-content-center">
            <b-tabs content-class="pt-1" fill>
                <b-tab title="Design" active>
                     <b-alert
                            variant="info"
                            show
                            class="mb-0"
                          >
                        <div>
                          <span class="mx-5">
                            <span class="mx-1">
                          <b-img
                          class="my-2"
                            :src="require('@/assets/images/menu/technologies/design/p1.png')"
                            alt="man image"
                          />
                            </span>
                          </span>
                         <span class="mx-5">
                            <span class="mx-1">
                          <b-img
                            :src="require('@/assets/images/menu/technologies/design/p2.png')"
                            alt="man image"
                          />
                            </span>
                          </span>

                           <span class="mx-5">
                            <span class="mx-1">
                          <b-img
                            :src="require('@/assets/images/menu/technologies/design/p3.png')"
                            alt="man image"
                          />
                            </span>
                          </span>
                           <span class="mx-5">
                            <span class="mx-1">
                          <b-img
                            :src="require('@/assets/images/menu/technologies/design/p4.png')"
                            alt="man image"
                          />
                            </span>
                          </span>
                           <span class="mx-5">
                            <span class="mx-1">
                          <b-img
                            :src="require('@/assets/images/menu/technologies/design/p5.png')"
                            alt="man image"
                          />
                            </span>
                          </span>
                        </div>
                    </b-alert>
                </b-tab>
                <b-tab title="DevOps">
                    <h1>hgggggggggggggggggggggggggggggg gggggggggggggggggggggg ggggggggggggggggggggggg ggggggggggggggggggggggggggggggg</h1>
                </b-tab>
                <b-tab title="Database">
                </b-tab>
                <b-tab title="Front  End">
                </b-tab>
            </b-tabs>
            </div>
          </b-col>
           <b-col xl="1"  md="1" >
          </b-col>
  </b-row>
</div>
</template>

<script>
import {
  BRow, BCol, BTabs, BTab, BAlert, BImg,
} from 'bootstrap-vue'

export default {
  components: {
    BRow,
    BCol,
    BTabs,
    BTab,
    BAlert,
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
