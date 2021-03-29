<template  >
<div>
<Nav />
<Banner />
<About/>
</div>
    
</template>
<script>
import About from './About.vue';
import Banner from './banner.vue';
import Nav from './nav.vue';

export default {
  components: {
    
    Nav,
    Banner,
    About,
   
  },
};
</script>
 