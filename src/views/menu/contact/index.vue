<template>
<div>
     <div>
      <b-row class="d-none d-lg-flex">
           <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center my-2">
         <h1> <b class="display-4">Contact</b> </h1>
               </div>
          </b-col>
      </b-row>
 </div>

  <div class="d-xl-none">
      <b-row >
          <b-col xl="12"  md="12" >
               <div class="d-flex justify-content-center mt-3">
                   <h2> <b>Contact</b> </h2>
                </div>
          </b-col>
      </b-row>
 </div>
 <div class="mt-5 d-none d-lg-flex">
     <b-row>
         <b-col xl="1"  md="1">
         </b-col>
         <b-col xl="10"  md="10">
                <b-card class="rounded-card">
                    <b-row>
                    <b-col xl="6"  md="6" >
                        <div class="my-3 ml-3 mt-3">
                    <h1> <b class="display-5">LET’S  TALK</b> </h1>
                    <h1> <b class="display-3">Speak With Expert Engineers.</b> </h1>
                        </div>
                        <b-row class="ml-2 mt-2">
                            <b-col
                            md="6"
                            sm="6"
                            class="mb-2 mb-md-0"
                            >
                            <b-media no-body>
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/usa.png')"
                                    alt="main image"
                                    width="65px"
                                    height="65px"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                    Call :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                    +1 (561) 859-9201
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <b-col
                            md="6"
                            sm="6"
                            class="mb-2 mb-md-0"
                            >
                            <b-media no-body>
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/sri.png')"
                                    alt="main image"
                                    width="65px"
                                    height="65px"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                    Call :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                    +94 76 640 8888
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <b-col
                            md="6"
                            sm="6"
                            class="mt-2 mb-2 mb-md-0"
                            >
                            <b-media no-body>
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/mail.png')"
                                    alt="main image"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                    Email :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                    info@voxitec.com
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <b-col
                            md="6"
                            sm="6"
                            class="mt-2 mb-2 mb-md-0"
                            >
                            <b-media no-body>
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/skype.png')"
                                    alt="main image"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                Skype :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                +94 760 8888
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                        </b-row>
                        <b-row>
                            <b-col
                            md="12"
                            sm="12"
                            class="mb-2 mb-md-0"
                            >
                            <b-media no-body class="ml-5 mt-5">
                                <b-media-body class="ml-3 mt-1">
                                <h2 class="font-weight-bolder mb-0 mr-4">
                                    <b-img
                                    :src="require('@/assets/images/menu/contact/coma.png')"
                                    alt="main image"
                                    width="60px"
                                    class="mt-n2"
                                    />
                                    <span class="ml-n2 ">We had an incredible experience working with Landify and were impressed they made such a big difference in only three weeks.
                                    </span></h2>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <div class="ml-5">
                           <h1 class="text-info ml-5 mt-3"><b> Scarlett Johansson</b> </h1>
                        </div>
                        </b-row>
                        <div class="ml-5">
                           <h2 class="ml-3 mt-0">CEO at Xion </h2>
                        </div>
                   </b-col>
                    <b-col xl="5"  md="5">
                         <b-form @submit.prevent>
                            <b-row>
                                <b-col cols="12">
                                 <h3 class="mt-3 mb-1"> <b class="display-5 my-5">Full Name</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <b-form-group
                                >
                                <b-input-group class="input-group-merge">
                                    <b-input-group-prepend is-text>
                                    <feather-icon icon="UserIcon" size="22rem" />
                                    </b-input-group-prepend>
                                    <b-form-input
                                    size="lg"
                                    id="hi-first-name"
                                    placeholder="First Name"
                                    />
                                </b-input-group>
                                </b-form-group>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Email</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <b-form-group
                                >
                                <b-input-group class="input-group-merge">
                                    <b-input-group-prepend is-text>
                                    <feather-icon icon="MailIcon" size="22rem"/>
                                    </b-input-group-prepend>
                                    <b-form-input
                                    size="lg"
                                    id="hi-email"
                                    type="email"
                                    placeholder="Email"
                                    />
                                </b-input-group>
                                </b-form-group>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Phone</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <b-form-group
                                >
                                <b-input-group class="input-group-merge">
                                    <b-input-group-prepend is-text>
                                    <feather-icon icon="SmartphoneIcon" size="22rem"/>
                                    </b-input-group-prepend>
                                    <b-form-input
                                    size="lg"
                                    id="hi-number"
                                    type="number"
                                    placeholder="Mobile"
                                    />
                                </b-input-group>
                                </b-form-group>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Select  a Service</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <div>
                                    <b-form-select
                                    v-model="selected"
                                    :options="options"
                                    size="lg"
                                    />
                                </div>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Describe your project in short</b> </h3>
                                </b-col>
                                <b-col cols="12">
                                <div>
                                        <!-- Plain mode -->
                                        <b-form-file
                                        v-model="file2"
                                        class="mt-1"
                                        plain
                                        >
                                        </b-form-file>
                                    </div>
                                </b-col>
                                <b-col cols="12">
                                 <h3 class="mt-2 mb-1">
                                    <feather-icon icon="PaperclipIcon" size="22rem"/><b class="display-5 ml-1 my-5">Attach file</b> </h3>
                                </b-col>
                            <!-- submit and reset -->
                            <b-col md="12" class="d-flex justify-content-center">
                                <b-button
                                v-ripple.400="'rgba(255, 255, 255, 0.15)'"
                                type="submit"
                                variant="info"
                                >
                                Let’s Discuss Your Project
                                </b-button>
                                <!-- <b-button
                                v-ripple.400="'rgba(186, 191, 199, 0.15)'"
                                type="reset"
                                variant="outline-secondary"
                                >
                                Reset
                                </b-button> -->
                            </b-col>
                            </b-row>
                        </b-form>
                    </b-col>
                    <b-col xl="1"  md="1">
                    </b-col>
                    </b-row>
                </b-card>
         </b-col>
         <b-col xl="1"  md="1">
         </b-col>
     </b-row>
 </div>
   <div class="mt-5 d-xl-none">
     <b-row>
         <b-col xl="1"  md="1">
         </b-col>
         <b-col xl="10"  md="10">
                <b-card class="rounded-card">
                    <b-row>
                   <b-col xl="6"  md="6">
                        <div class="my-3 ml-3 mt-3" align="center">
                    <h3> <b >LET’S  TALK</b> </h3>
                    <h1> <b class="display-5">Speak With Expert Engineers.</b> </h1>
                        </div>
                        <b-row class="ml-2 mt-2">
                            <b-col
                            md="6"
                            sm="6"
                            class="mb-2 mb-md-0"
                            >
                            <b-media no-body class="ml-5">
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/usa.png')"
                                    alt="main image"
                                    width="65px"
                                    height="65px"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                    Call :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                    +1 (561) 859-9201
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <b-col
                            md="6"
                            sm="6"
                            class="mb-2 mb-md-0"
                            >
                            <b-media no-body class="ml-5">
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/sri.png')"
                                    alt="main image"
                                    width="65px"
                                    height="65px"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                    Call :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                    +94 76 640 8888
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <b-col
                            md="6"
                            sm="6"
                            class="mt-2 mb-2 mb-md-0"
                            >
                            <b-media no-body class="ml-5">
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/mail.png')"
                                    alt="main image"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                    Email :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                    info@voxitec.com
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                            <b-col
                            md="6"
                            sm="6"
                            class="mt-2 mb-2 mb-md-0"
                            >
                            <b-media no-body class="ml-5">
                                <b-media-aside class="mr-2">
                                <b-img
                                    :src="require('@/assets/images/menu/contact/skype.png')"
                                    alt="main image"
                                    />
                                </b-media-aside>
                                <b-media-body class="my-auto">
                                <h4 class="font-weight-bolder mb-0">
                                Skype :
                                </h4>
                                <h4 class="font-weight-bolder mb-0">
                                +94 760 8888
                                </h4>
                                </b-media-body>
                            </b-media>
                            </b-col>
                        </b-row>
                        <b-row>
                            <b-col
                            md="12"
                            sm="12"
                            class="mb-2 mb-md-0"
                            >
                            <b-media no-body align="center" class="mt-5">
                                <b-media-body class="mt-1">
                                <h2 class="font-weight-bolder mb-0">
                                    <b-img
                                    :src="require('@/assets/images/menu/contact/coma.png')"
                                    alt="main image"
                                    width="60px"
                                    class="mt-n2"
                                    />
                                    <span class="ml-n2">We had an incredible experience working with Landify and were impressed they made such a big difference in only three weeks.
                                    </span></h2>
                                </b-media-body>
                            </b-media>
                            </b-col>
                        </b-row>
                        <div class="d-flex justify-content-center">
                           <h1 class="text-info mt-3"><b> Scarlett Johansson</b> </h1>
                        </div>
                        <div class="d-flex justify-content-center">
                           <h2 class="mt-0">CEO at Xion </h2>
                        </div>
                   </b-col>
                    <b-col xl="5"  md="5">
                         <b-form @submit.prevent>
                            <b-row>
                                <b-col cols="12">
                                 <h3 class="mt-3 mb-1"> <b class="display-5 my-5">Full Name</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <b-form-group
                                >
                                <b-input-group class="input-group-merge">
                                    <b-input-group-prepend is-text>
                                    <feather-icon icon="UserIcon" />
                                    </b-input-group-prepend>
                                    <b-form-input
                                    size="lg"
                                    id="hi-first-name"
                                    placeholder="First Name"
                                    />
                                </b-input-group>
                                </b-form-group>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Email</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <b-form-group
                                >
                                <b-input-group class="input-group-merge">
                                    <b-input-group-prepend is-text>
                                    <feather-icon icon="MailIcon" />
                                    </b-input-group-prepend>
                                    <b-form-input
                                    size="lg"
                                    id="hi-email"
                                    type="email"
                                    placeholder="Email"
                                    />
                                </b-input-group>
                                </b-form-group>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Phone</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <b-form-group
                                >
                                <b-input-group class="input-group-merge">
                                    <b-input-group-prepend is-text>
                                    <feather-icon icon="SmartphoneIcon" />
                                    </b-input-group-prepend>
                                    <b-form-input
                                    size="lg"
                                    id="hi-number"
                                    type="number"
                                    placeholder="Mobile"
                                    />
                                </b-input-group>
                                </b-form-group>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Select  a Service</b> </h3>
                                </b-col>
                            <b-col cols="12">
                                <div>
                                    <b-form-select
                                    v-model="selected"
                                    :options="options"
                                    size="lg"
                                    />
                                </div>
                            </b-col>
                            <b-col cols="12">
                                 <h3 class="mt-2 mb-1"> <b class="display-5 my-5">Describe your project in short</b> </h3>
                                </b-col>
                                <b-col cols="12">
                                <div>
                                        <!-- Plain mode -->
                                        <b-form-file
                                        v-model="file2"
                                        class="mt-1"
                                        plain
                                        >
                                        </b-form-file>
                                    </div>
                                </b-col>
                                <b-col cols="12">
                                 <h3 class="mt-2 mb-1">
                                    <feather-icon icon="PaperclipIcon" size="22rem"/><b class="display-5 ml-1 my-5">Attach file</b> </h3>
                                </b-col>
                            <!-- submit and reset -->
                            <b-col md="12" class="d-flex justify-content-center">
                                <b-button
                                v-ripple.400="'rgba(255, 255, 255, 0.15)'"
                                type="submit"
                                variant="info"
                                >
                                Let’s Discuss Your Project
                                </b-button>
                                <!-- <b-button
                                v-ripple.400="'rgba(186, 191, 199, 0.15)'"
                                type="reset"
                                variant="outline-secondary"
                                >
                                Reset
                                </b-button> -->
                            </b-col>
                            </b-row>
                        </b-form>
                    </b-col>
                    <b-col xl="1"  md="1">
                    </b-col>
                    </b-row>
                </b-card>
         </b-col>
         <b-col xl="1"  md="1">
         </b-col>
     </b-row>
 </div>
</div>
</template>

<script>
import {
  BRow, BFormSelect, BCol, BImg, BCard, BMedia, BMediaAside, BFormFile, BMediaBody, BFormGroup, BFormInput, BForm, BButton, BInputGroup, BInputGroupPrepend,
} from 'bootstrap-vue'

export default {
  components: {
    BMedia,
    BMediaBody,
    BRow,
    BMediaAside,
    BCol,
    BImg,
    BCard,
    BFormFile,
    BFormGroup,
    BFormInput,
    BInputGroup,
    BInputGroupPrepend,
    BForm,
    BButton,
    BFormSelect,
  },
  data() {
    return {
      selected: null,
      options: [
        { value: null, text: 'Please select an option' },
        { value: 'a', text: 'This is First option' },
        { value: 'b', text: 'Simple Option' },
        { value: { C: '3PO' }, text: 'This is an option with object value' },
        { value: 'd', text: 'This one is disabled', disabled: true },
      ],
    }
  },
}
</script>

<style>
.rounded-card{
    border-radius:50px;
}

</style>
