<template>
  <section>
    <div class="container py-5">
      <div class="row">
        <div class="col-12">
          <div
            class="poy-sian d-none d-sm-none d-md-block d-lg-block"
            data-aos="fade-up"
          >
            <img
              :src="inp"
              class="d-block mx-auto img-fluid"
              width="1000"
              height="1000"
              alt="..."
            />
          </div>

          <div class="d-block d-sm-block d-md-none mt-5">
            <img :src="inp" class="d-block mx-auto img-fluid" alt="..." />
          </div>
        </div>

        <div class="box1">
          <div class="row">
            <div
              class="d-sm-flex align-items-center justify-content-between py-5"
            >
              <div
                class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5"
                data-aos="fade-up"
              >
                <h1 class="text-center text-lg-start mb-3" style="font-size: 80px;">
                  Standard, <br />
                  Popularity
                </h1>
                <p class="text-center text-lg-start fs-3">
                  POY-SIAN is *number <span class="fw-bold fs-1">1</span> in the inhaler market with <br /> <span class="text-decoration-underline fw-bold">70%</span> market share. <br /><br />
                  <span class="text-white-50">*Data from Peppermint, 2019</span>
                </p>
              </div>

              <div class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5">
                <div class="container" data-aos="fade-down">
                  <video controls autoplay>
                    <source :src="videop" type="video/mp4" />
                    Your browser does not support the video tag.
                  </video>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="box2">
          <div class="row">
            <div
              class="d-sm-flex align-items-center justify-content-between py-5"
            >
              <div class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5">
                <div class="container" data-aos="fade-down">
                  <img :src="inht" class="img-fluid" alt="..." />
                </div>
              </div>

              <div
                class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5"
                data-aos="fade-up"
              >
                <h1 class="text-center text-lg-start mb-3" style="font-size: 45px;">
                  Both inhaling and applying in the <span class="text-decoration-underline">SAME TUBE!</span>
                </h1>
                <p class="text-center text-lg-start fs-3">
                  Yes, this is Thailand's first inhaler brand. with both inhalers and topical in the same tube
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer class="container-fluid p-3" style="background-color: #222324;">
      <div class="container">
        <p class="text-white text-center">&copy; 2022 All Rights Reserved <br/> For COS001 Media Studies | Term Project Only</p>
      </div>
    </footer>
  </section>
</template>

<script>
import { onMounted } from "vue";
import AOS from "aos";

export default {
  name: "App",
  components: {},

  data() {
    return {
      inp: require("./assets/h-1.png"),
      inp2: require("./assets/h-1m.png"),
      videop: require("./assets/gg.mp4"),
      inht: require("./assets/inh-t.png"),
    };
  },

  setup() {
    onMounted(() => {
      AOS.init();
    });
  },
};
</script>

<style>
body {
  background: rgb(214, 70, 77);
  background: linear-gradient(
    90deg,
    rgba(214, 70, 77, 1) 0%,
    rgba(105, 159, 203, 1) 100%
  );
  font-family: "Times New Roman", Times, serif;
  color: white;
}

video {
  width: 100%;
  height: auto;
}
</style>
