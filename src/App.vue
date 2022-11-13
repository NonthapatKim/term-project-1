<template>
  <div class="container">
    <div class="row">
      <div class="col-12">
        <div class="poy-sian" data-aos="fade-up">
          <img :src="inp" class="d-block mx-auto img-fluid" alt="..." />
        </div>
      </div>
    </div>
  </div>  
</template>

<script>
import { onMounted } from "vue";
import AOS from "aos";


export default {
  name: 'App',
  components: {
    
  },
  
  data() {
    return {
      inp: require("./assets/h-1.png")
    }
  },

  setup() {
    onMounted(() => {
      AOS.init();
    })
  }
}
</script>

<style>
body {
  background: rgb(214,70,77);
  background: linear-gradient(90deg, rgba(214,70,77,1) 0%, rgba(105,159,203,1) 100%);
}
</style>
