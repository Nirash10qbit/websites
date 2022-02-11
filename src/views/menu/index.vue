<template>
<div>
<div>
    <MainPage></MainPage>
</div>
<div>
    <WhoPage></WhoPage>
</div>
<div>
    <ProcessPage></ProcessPage>
</div>
<div>
    <DeveloperPage></DeveloperPage>
</div>
<div>
    <TechnologyPage></TechnologyPage>
</div>
<div>
    <IndustriesPage></IndustriesPage>
</div>
<div>
    <BlogPage></BlogPage>
</div>
<div>
    <ContactPage></ContactPage>
</div>
<div>
    <FooterPage></FooterPage>
</div>
</div>
</template>

<script>
import MainPage from '@/views/menu/main/index.vue'
import WhoPage from '@/views/menu/who/index.vue'
import ProcessPage from '@/views/menu/process/index.vue'
import DeveloperPage from '@/views/menu/developer/index.vue'
import TechnologyPage from '@/views/menu/technologies/index.vue'
import IndustriesPage from '@/views/menu/industries/index.vue'
import BlogPage from '@/views/menu/blogs/index.vue'
import ContactPage from '@/views/menu/contact/index.vue'
import FooterPage from '@/views/menu/footer/index.vue'

export default {
  components: {
    MainPage,
    WhoPage,
    ProcessPage,
    DeveloperPage,
    TechnologyPage,
    IndustriesPage,
    BlogPage,
    ContactPage,
    FooterPage,

  },
  data() {
    return {
    }
  },
}
</script>

<style lang="scss">
</style>
