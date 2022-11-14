<template>
  <section>
    <div class="container-fluid bg-g py-5">
      <div class="container">
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
                class="
                  d-sm-flex
                  align-items-center
                  justify-content-between
                  py-5
                "
              >
                <div
                  class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5"
                  data-aos="fade-up"
                >
                  <h1
                    class="text-center text-lg-start mb-3"
                    style="font-size: 70px; font-weight: bold; font-style: italic;"
                  >
                    Standard, <br />
                    Popularity
                  </h1>
                  <p class="text-center text-lg-start fs-3">
                    POY-SIAN is *number <span class="fw-bold fs-1">1</span> in
                    the inhaler market with <br />
                    <span class="text-decoration-underline fw-bold">70%</span>
                    market share. <br /><br />
                    <span class="text-white-50"
                      >*Data from Peppermint brand, 2019</span
                    >
                  </p>
                </div>

                <div class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5">
                  <div class="container" data-aos="fade-down">
                    <video autoplay muted loop>
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
                class="
                  d-sm-flex
                  align-items-center
                  justify-content-between
                  py-5
                "
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
                  <h1
                    class="text-center text-lg-start mb-3"
                    style="font-size: 45px; font-weight: bold; font-style: italic;"
                  >
                    Both inhaling and applying in the
                    <span class="text-decoration-underline">SAME TUBE!</span>
                  </h1>
                  <p class="text-center text-lg-start fs-3">
                    Yes, We're Thailand's first inhaler brand. with both inhalers and topical in the same tube!
                  </p>
                </div>
              </div>
            </div>
          </div>

          <div class="box3">
            <div class="row">
              <div
                class="
                  d-sm-flex
                  align-items-center
                  justify-content-between
                  py-5
                "
              >
                <div
                  class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5"
                  data-aos="fade-up"
                >
                  <h1
                    class="text-center text-lg-start mb-3"
                    style="font-size: 45px; font-weight: bold; font-style: italic;"
                  >
                  Details
                  </h1>
                  <p class="text-center text-lg-start fs-3">
                    <ul>
                      <li>
                        Relieve dizziness stuffy nose from a cold
                      </li>

                      <li>
                        Can be used for both inhaling and applying in the same tube or drop into a handkerchief, inhale
                      </li>


                      <li>
                        Ingredients: Menthol, camphor, eucalyptus oil, patchouli
                      </li>
                    </ul>
                  </p>
                </div>

                <div class="col-12 col-sm-12 col-md-12 col-lg-6 mt-5">
                  <div class="container" data-aos="fade-down">
                    <img :src="inht2" class="img-fluid" alt="..." />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid shop py-5">
      <div class="container">
        <h2 class="text-white mb-3 fw-bold">All Products | สินค้าทั้งหมด</h2>

        <div class="row">
          <div class="col-12 col-sm-12 col-md-4 col-lg-4 mb-3">
            <div class="card p-4">
              <img :src="p1" class="img-fluid" width="500" alt="..." />

              <div class="detaill mt-4">
                <h4 class="fw-bold">ยาดมตรา "โป๊ยเซียน" คละสี (x1)</h4>
                <p class="text-muted">ยาดมตรา "โป๊ยเซียน" คละสี จำนวน 1 ชิ้น</p>

                <div class="d-flex align-items-center justify-content-between">
                  <div class="stock">
                    <p>เหลืออยู่ในคลัง: <span class="text-danger fs-5 fw-bold">105</span></p>
                  </div>

                  <div class="price">
                    <p><span class="text-primary fs-2 fw-bold">20</span> บาท</p>
                  </div>
                </div>
              </div>

              <a type="button" class="btn btn-primary fw-bold">หยิบใส่ตะกร้า</a>
            </div>
          </div>

          <div class="col-12 col-sm-12 col-md-4 col-lg-4 mb-3">
            <div class="card p-4">
              <img :src="p2" class="img-fluid" width="500" alt="..." />

              <div class="detaill mt-4">
                <h4 class="fw-bold">ยาดมตรา "โป๊ยเซียน" คละสี (x3)</h4>
                <p class="text-muted">ยาดมตรา "โป๊ยเซียน" คละสี จำนวน 3 ชิ้น/แพ็ค</p>

                <div class="d-flex align-items-center justify-content-between">
                  <div class="stock">
                    <p>เหลืออยู่ในคลัง: <span class="text-danger fs-5 fw-bold">50</span></p>
                  </div>

                  <div class="price">
                    <p><span class="text-primary fs-2 fw-bold">59</span> บาท</p>
                  </div>
                </div>
              </div>

              <a type="button" class="btn btn-primary fw-bold">หยิบใส่ตะกร้า</a>
            </div>
          </div>

          <div class="col-12 col-sm-12 col-md-4 col-lg-4 mb-3">
            <div class="card p-4">
              <img :src="p3" class="img-fluid" width="500" alt="..." />

              <div class="detaill mt-4">
                <h4 class="fw-bold">ยาดมตรา "โป๊ยเซียน" คละสี (x6)</h4>
                <p class="text-muted">ยาดมตรา "โป๊ยเซียน" คละสี จำนวน 6 ชิ้น/แพ็ค</p>

                <div class="d-flex align-items-center justify-content-between">
                  <div class="stock">
                    <p>เหลืออยู่ในคลัง: <span class="text-danger fs-5 fw-bold">34</span></p>
                  </div>

                  <div class="price">
                    <p><span class="text-primary fs-2 fw-bold">118</span> บาท</p>
                  </div>
                </div>
              </div>

              <a type="button" class="btn btn-primary fw-bold">หยิบใส่ตะกร้า</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="d-sm-flex align-items-center justify-content-between py-5">
          <div class="col-12 col-sm-12 col-md-12 col-lg-6">
            <img :src="ctimg" class="img-fluid" alt="..." />
          </div>

          <div class="col-12 col-sm-12 col-md-12 col-lg-6">
            <h1 class="fw-bold">Contact Us</h1>

            <form>
              <div class="row mt-3">
                <div class="col form-outline mb-3">
                  <label for="fname" class="form-label">First name</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="First name"
                  />
                </div>

                <div class="col form-outline mb-3">
                  <label for="lname" class="form-label">Last name</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Last name"
                  />
                </div>

                <div class="col-12 form-outline mb-3">
                  <label for="email" class="form-label">Email address</label>
                  <input type="email" class="form-control" placeholder="Email" />
                </div>

                <div class="col-12 form-outline mb-3">
                  <label for="phonenumber" class="form-label">Phone Number</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Eg. +66 00 0000000"
                  />
                </div>

                <div class="col-12 form-outline mb-3">
                  <label for="msg" class="form-label">message</label>
                  <textarea
                    class="form-control"
                    rows="10"
                    placeholder="Message"
                  ></textarea>
                </div>
              </div>

              <button type="button" class="btn btn-primary">Submit</button>
            </form>
          </div>
        </div>
      </div>
    </div>

    <footer class="container-fluid p-3" style="background-color: #222324">
      <div class="container">
        <p class="text-white text-center">
          &copy; 2022 All right reserved <br />
          For COS001 Media Studies | Term Project Only
        </p>
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
      ctimg: require("./assets/contect-us.png"),
      inht2: require("./assets/inh-2.png"),

      p1: require("./assets/product-1.png"),
      p2: require("./assets/product-2.png"),
      p3: require("./assets/product-3.png"),
      p4: require("./assets/product-4.png"),
      p5: require("./assets/product-5.png"),
      p6: require("./assets/product-6.png"),
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
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@400;500;600;700&display=swap');

body {
  font-family: Helvetica, sans-serif;
}

.bg-g {
  background-color: #037A35;
  color: #fff7f7;
}

video {
  width: 100%;
  height: auto;
}

.form-label {
  text-transform: uppercase;
}

.shop {
  font-family: 'Noto Sans Thai', sans-serif;
  background-color: #D46777;
}

.card {
  border: none;
  border-radius: 20px;
}

.card img{
  border-radius: 20px;
}
</style>
