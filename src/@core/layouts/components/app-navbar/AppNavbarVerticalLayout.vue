<template>
  <div class="navbar-container d-flex content align-items-center">

    <b-navbar-nav class="nav align-items-center">
      <div class="mt-4 mb-2 ml-4">
        <h2>
        <b-img
                  :src="require('@/assets/images/menu/logos.png')"
                  alt="Generic placeholder image"
                  height="55"
                  width="55"
                  class="ml-2"
                />
        <b class="ml-2">VOXITEC</b></h2>
      </div>
    </b-navbar-nav>

    <!-- Nav Menu Toggler -->
    <ul class="nav navbar-nav d-xl-none ml-auto">
      <li class="nav-item">
        <b-link
          class="nav-link"
          @click="toggleVerticalMenuActive"
        >
          <feather-icon
            icon="MenuIcon"
            size="21"
          />
        </b-link>
      </li>
    </ul>

    <!-- Left Col -->
    <div class=" d-none d-lg-flex ml-auto mt-0">

      <!-- Bookmarks Container -->
      <div class="mt-2 ">
        <h4><b class="ml-3 ">About</b></h4>
      </div>
      <div class="ml-3 mt-2 ">
        <h4><b class="ml-3 ">Services</b></h4>
      </div>
      <div class="ml-3 mt-2 ">
        <h4><b class="ml-3 ">Technologies</b></h4>
      </div>
      <div class="ml-3 mt-2 ">
        <h4><b class="ml-3 ">Projects</b></h4>
      </div>
      <div class="ml-5 mt-1 mr-5">
        <b-button
            class="rounded-pill"
            v-ripple.400="'rgba(255, 255, 255, 1)'"
            variant="info"
        >
          Get Touch
        </b-button>
      </div>
      <dark-Toggler class="d-none d-lg-block ml-2 mt-1" />
    </div>
  </div>
</template>

<script>
import {
  BButton, BLink, BNavbarNav, BImg,
} from 'bootstrap-vue'
import Ripple from 'vue-ripple-directive'
import DarkToggler from './components/DarkToggler.vue'

export default {
  directives: {
    Ripple,
  },
  components: {
    DarkToggler,
    BButton,
    BImg,
    BLink,
    BNavbarNav,
  },
  props: {
    toggleVerticalMenuActive: {
      type: Function,
      default: () => {},
    },
  },
}
</script>
<style>

</style>
