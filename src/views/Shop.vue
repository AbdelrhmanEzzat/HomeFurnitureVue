<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            <div class="brand">
              <div class="shoptitle"></div>
              <h1 class="shopmain">Shop</h1>
              <h3 class="shopmain"></h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
    <!-- Font Awesome -->
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css"
      rel="stylesheet"
    />
    <!-- Google Fonts -->
    <link
      href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
      rel="stylesheet"
    />
    <!-- MDB -->
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/3.10.2/mdb.min.css"
      rel="stylesheet"
    />

    <!-- ----------------------------Filter---------------------------------- -->
    <div class="main main-raised">
      <div class="section section-basic">
        <link
          rel="stylesheet"
          href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/css/all.min.css"
          integrity="sha256-2XFplPlrFClt0bIdPgpz8H7ojnk10H69xRqd9+uTShA="
          crossorigin="anonymous"
        />

        <div class="container">
          <div class="row" style="width:100%">
            <div class="col-lg-3">
              <div class="sidebar">
                <div class="widget border-0">
                  <div class="search">
                    <input
                      class="form-control"
                      type="text"
                      placeholder="Search Keywords"
                    />
                  </div>
                </div>

                <div class="widget">
                  <div class="widget-title widget-collapse">
                    <h6>Filter By Categories</h6>
                    <a
                      class="ml-auto"
                      data-toggle="collapse"
                      href="#dateposted"
                      role="button"
                      aria-expanded="false"
                      aria-controls="dateposted"
                    >
                    </a>
                  </div>
                  <div class="collapse show" id="dateposted">
                    <div class="widget-content">
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="dateposted1"
                        />
                        <label class="custom-control-label" for="dateposted1"
                          >Dining Chair</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="dateposted2"
                        />
                        <label class="custom-control-label" for="dateposted2"
                          >Lounge Chair</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="dateposted3"
                        />
                        <label class="custom-control-label" for="dateposted3"
                          >Office Chair</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="dateposted4"
                        />
                        <label class="custom-control-label" for="dateposted4"
                          >Bedroom Chair</label
                        >
                      </div>
                    </div>
                  </div>
                </div>
                <div class="widget">
                  <div class="widget-title widget-collapse">
                    <h6>Filter By Color</h6>
                    <a
                      class="ml-auto"
                      data-toggle="collapse"
                      href="#specialism"
                      role="button"
                      aria-expanded="false"
                      aria-controls="specialism"
                    >
                    </a>
                  </div>
                  <div class="collapse show" id="specialism">
                    <div class="widget-content">
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="specialism1"
                        />
                        <label class="custom-control-label" for="specialism1"
                          >Red</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="specialism2"
                        />
                        <label class="custom-control-label" for="specialism2"
                          >Green</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="specialism3"
                        />
                        <label class="custom-control-label" for="specialism3">
                          Blue</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="specialism4"
                        />
                        <label class="custom-control-label" for="specialism4"
                          >Silver</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="specialism5"
                        />
                        <label class="custom-control-label" for="specialism5"
                          >Black</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="specialism5"
                        />
                        <label class="custom-control-label" for="specialism5"
                          >Brown</label
                        >
                      </div>
                    </div>
                  </div>
                </div>
                <div class="widget">
                  <div class="widget-title widget-collapse">
                    <h6>Filter By Fabric</h6>
                    <a
                      class="ml-auto"
                      data-toggle="collapse"
                      href="#jobtype"
                      role="button"
                      aria-expanded="false"
                      aria-controls="jobtype"
                    >
                    </a>
                  </div>
                  <div class="collapse show" id="jobtype">
                    <div class="widget-content">
                      <div class="custom-control custom-checkbox fulltime-job">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="jobtype1"
                        />
                        <label class="custom-control-label" for="jobtype1"
                          >Alpaca wollen fabric</label
                        >
                      </div>

                      <div class="custom-control custom-checkbox freelance-job">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="jobtype3"
                        />
                        <label class="custom-control-label" for="jobtype3"
                          >Boiled wollen fabric</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox temporary-job">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="jobtype4"
                        />
                        <label class="custom-control-label" for="jobtype4"
                          >Crepe Fabric</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox temporary-job">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="jobtype4"
                        />
                        <label class="custom-control-label" for="jobtype4"
                          >Jute fabric</label
                        >
                      </div>
                      <div class="custom-control custom-checkbox temporary-job">
                        <input
                          type="checkbox"
                          class="custom-control-input"
                          id="jobtype4"
                        />
                        <label class="custom-control-label" for="jobtype4"
                          >Wollen fabric</label
                        >
                      </div>
                    </div>
                  </div>
                </div>
                <div class="widget">
                  <div class="widget-title widget-collapse">
                    <h6>Filter By Price</h6>

                    <a
                      class="ml-auto"
                      data-toggle="collapse"
                      href="#jobtype"
                      role="button"
                      aria-expanded="false"
                      aria-controls="jobtype"
                    >
                    </a>
                  </div>
                  <div class="collapse show" id="jobtype">
                    <div class="widget-content">
                      <div class="custom-control custom-checkbox fulltime-job">
                        <div id="sliders">
                          <div
                            class="md-layout-item md-size-150 md-xsmall-size-200"
                            style="width: 100%;height:50%;"
                          >
                            <slider
                              v-model="sliders.rangeSlider"
                              type="info"
                              :connect="true"
                            >
                            </slider>
                            <h6>
                              Price: £0 — £4,000
                            </h6>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!-- ------------------- -->


                        <div class="col-lg-9">
                <div class="row mt-4">
                    <div class="col-lg-4 col-md-6 mb-4" v-for="item in list" v-bind:key="item.id"  
              v-bind:item="item">
                        <div class="card h-100">
                            <a href="#">
                                <img class="card-img-top" src="http://placehold.it/700x400" alt="">
                            </a>
                            <div class="card-body">
                                <h4 class="card-title">
                                    <a href="#">{{ item.product_name  }}</a>
                                </h4>
                                <h5>$ {{ item.cost }}</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- <div  class="col-md-9">
              <div v-for="item in list" v-bind:key="item.id"  
              v-bind:item="item"
              >
                <div  class="row product-list">
                  <div class="col-md-4">
                    <div class="product-grid7">
                      <div class="product-image7">
                        <a href="#/SingleProduct">
                          <img class="pic-1" :src="img1" />
                          <img class="pic-2" :src="img01" />
                        </a>
                        <ul class="social">
                          <li><a href="" class="fa fa-search"></a></li>
                          <li><a href="" class="fa fa-shopping-bag"></a></li>
                          <li><a href="" class="fa fa-shopping-cart"></a></li>
                        </ul>
                        <span class="product-new-label">NEW</span>
                      </div>
                      <div class="product-content">
                        <h3 class="title">
                          <a href="#" >{{ item.product_name }}</a>
                        </h3>
                        <ul class="rating">
                          <li class="fa fa-star"></li>
                          <li class="fa fa-star"></li>
                          <li class="fa fa-star"></li>
                        </ul>
                        <div class="price">
                          {{ item.cost }}
                         
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script
  type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/3.10.2/mdb.min.js"
></script>

<script>
import Vue from "vue";
import axios from "axios";
import VueAxios from "vue-axios";
Vue.use(VueAxios, axios);
import { Slider } from "@/components";

export default {
  components: { Slider },
  name: "shop",
  bodyClass: "shop-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/shopback.jpg"),
    },
    img1: {
      type: String,
      default: require("@/assets/img/shop/1.jpg"),
    },
    img01: {
      type: String,
      default: require("@/assets/img/shop/1+.jpg"),
    },
    img2: {
      type: String,
      default: require("@/assets/img/shop/2.jpg"),
    },
    img02: {
      type: String,
      default: require("@/assets/img/shop/2+.jpg"),
    },
    img3: {
      type: String,
      default: require("@/assets/img/shop/3.jpg"),
    },
    img4: {
      type: String,
      default: require("@/assets/img/shop/4.jpg"),
    },
    img5: {
      type: String,
      default: require("@/assets/img/shop/5.jpg"),
    },
    img6: {
      type: String,
      default: require("@/assets/img/shop/6.jpg"),
    },
    img06: {
      type: String,
      default: require("@/assets/img/shop/6+.jpg"),
    },
    img7: {
      type: String,
      default: require("@/assets/img/shop/7.jpg"),
    },
    img07: {
      type: String,
      default: require("@/assets/img/shop/7+.jpg"),
    },
    img8: {
      type: String,
      default: require("@/assets/img/shop/8.jpg"),
    },
    img9: {
      type: String,
      default: require("@/assets/img/shop/9.jpg"),
    },
    img10: {
      type: String,
      default: require("@/assets/img/shop/10.jpg"),
    },
    img010: {
      type: String,
      default: require("@/assets/img/shop/10+.jpg"),
    },
    img11: {
      type: String,
      default: require("@/assets/img/shop/11.jpg"),
    },
    img12: {
      type: String,
      default: require("@/assets/img/shop/12.jpg"),
    },
    img012: {
      type: String,
      default: require("@/assets/img/shop/12+.jpg"),
    },
  },
  data() {
    return {
      sliders: {
        simple: 40,
        rangeSlider: [20, 60],
        
      },
        list: [],
      errors: []
    };
  },
  // async mounted() {
  //   await Vue.axios
  //     .get("https://homefurniture00.000webhostapp.com/api/products")
  //     .then((resp) => {
  //       this.list = resp.data;
  //       console.warn(resp.data);
  //     });
  // },


// created() {
//     axios.get(`https://homefurniture00.000webhostapp.com/api/products`)
//     .then(response => {
//       // JSON responses are automatically parsed.
//       this.list = response.data
//     })
//     .catch(e => {
//       this.errors.push(e)
//     })
//   },
// Fetches posts when the component is created.
  async created() {
    try {
      const response = await axios.get(`https://homefurniture00.000webhostapp.com/api/products`)
      this.list = response.data
    } catch (e) {
      this.errors.push(e)
    }
  },
  
  methods: {},
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.image})`,
      };
    },
  },
};
</script>

<style lang="scss">
/* Title */
.shoptitle {
  color: white;
  position: absolute;
  left: 50%;
  display: flex;

  align-items: center;
  text-align: center;
  width: 90%;
}
.shopmain {
  align-items: center;
  text-align: center;
  color: white;
}

/* checkbox */
.widget .widget-content {
  margin-top: 10px;
}
.widget .widget-content .custom-checkbox {
  margin-bottom: 8px;
}

/* Job Detail */

.widget .jobster-company-view ul li:last-child {
  margin-bottom: 0;
}

.sidebar .widget {
  border: 1px solid #e7e6eb;
  margin-bottom: 30px;
  width: 85%;
}
.sidebar .widget .widget-title {
  border-bottom: 1px solid #eeeeee;
  padding: 14px 20px;
}

.sidebar .widget .widget-content {
  padding: 14px 20px;
}
.custom-control-label {
  padding-left: 5%;
}
/* Shopping Demo */
.product-grid7 .product-image7 {
  border: 1px solid rgba(0, 0, 0, 0.1);
  overflow: hidden;
  perspective: 1500px;
  position: relative;
}
.product-grid7 .product-image7 a {
  display: block;
}
.product-grid7 .product-image7 img {
  width: 100%;
  height: auto;
}

.product-grid7 .pic-2 {
  opacity: 0;
  transform: rotateY(-90deg);
  position: absolute;
  top: 0;
  left: 0;
  transition: all 0.5s ease-out 0s;
}
.product-grid7:hover .pic-2 {
  opacity: 1;
  transform: rotateY(0);
}
.product-grid7 .social {
  padding: 0;
  margin: 0;
  list-style: none;
  position: absolute;
  bottom: 3px;
  left: -20%;
  z-index: 1;
  transition: all 0.5s ease 0s;
}
.product-grid7:hover .social {
  left: 17px;
}
.product-grid7 .social li a {
  color: #fff;
  background-color: #333;
  font-size: 16px;
  line-height: 40px;
  text-align: center;
  height: 40px;
  width: 40px;
  margin: 15px 0;
  border-radius: 50%;
  display: block;
}
.product-grid7 .social li a:hover {
  color: #fff;
  background-color: #bdbdbd;
}
.product-grid7 .product-new-label {
  color: #fff;
  background-color: #333;
  padding: 5px 10px;
  border-radius: 5px;
  display: block;
  position: absolute;
  top: 10px;
  left: 10px;
}
.product-grid7 .product-content {
  text-align: center;
  padding: 20px 0 0;
}
.product-grid7 .title {
  font-size: 15px;
  font-weight: 600;
  margin: 0 0 10px;
}

.product-grid7 .rating {
  color: #b60c0c;
  font-size: 12px;
  padding: 0;
  margin: 0 0 10px;
  list-style: none;
}
.product-grid7 .price {
  color: #333;
  font-size: 20px;
  font-family: Lora, serif;
  font-weight: 700;
  margin-bottom: 8px;
  text-align: center;
  transition: all 0.3s;
}
.product-grid7 .price span {
  color: #999;
  font-size: 14px;
  font-weight: 700;
  text-decoration: line-through;
  margin-left: 7px;
  display: inline-block;
}
</style>
