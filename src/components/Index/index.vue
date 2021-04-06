<template  >
  <div>
    <Nav />
    <Banner   id="banner" />
    <About    id="about" />
    <Projects id="projects" />
    <Contact  id="contact" />
  </div>
</template>
<script>
import About from "./About.vue";
import Banner from "./banner.vue";
import Contact from './Contact.vue';
import Nav from "./nav.vue";
import Projects from "./Projects.vue";

export default {
  components: {
    Nav,
    Banner,
    About,
    Projects,
    Contact,
  },
};
</script>
 