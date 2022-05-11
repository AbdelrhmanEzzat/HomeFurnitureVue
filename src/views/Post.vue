<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            <div class="brand">
              <div class="shoptitle"></div>
              <h1 class="shopmain">Posts</h1>
              <h3 class="shopmain">
                The real journey of discovery does not require going to a new
                land, but <br />
                rather it requires seeing with new eyes.
              </h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
    <!-- ----------------------------------------------------------- -->
    <div class="main main-raised">
      <div class="section section-basic">
        <div class="container">
          <div class="container bootstrap snippets bootdey">
            <div class="row">
              <div
                class="col-lg-8 col-md-12 left-box"
                style="width: 75%; padding: 0% 3%;"
              >
                <div class="card" style="  background: #fcfcfc;">
                  <div class="panel-blog-container">
                    <div class="panel-body">
                      <div class="image-wrapper">
                        <carousel
                          :per-page="1"
                          loop
                          :speed="700"
                          :autoplay-timeout="5000"
                          :mouse-drag="false"
                          navigationEnabled
                          navigationNextLabel="<i class='material-icons'>keyboard_arrow_right</i>"
                          navigationPrevLabel="<i class='material-icons'>keyboard_arrow_left</i>"
                        >
                          <slide>
                            <div class="carousel-caption"></div>
                            <img :src="carousel1" alt="carousel1" />
                          </slide>
                          <slide>
                            <div class="carousel-caption"></div>
                            <img :src="carousel2" alt="carousel2" />
                          </slide>
                        </carousel>
                      </div>
                      <!-------- Post1 -------->
                      <div class="widget-blog-author">
                        <div class="widget-blog-author-image">
                          <img
                            style="width:60px; height:60px"
                            :src="img"
                            alt=""
                          />
                        </div>
                      </div>
                      <h4>SÖDERHAMN Living Room</h4>
                      <div class="text">
                        <small class="text-muted"
                          >By
                          <a href="#/Profile"
                            ><strong>Abdelraman Ezzet</strong></a
                          >
                          | Post on January 20, 2022 | 70 comments</small
                        >
                        <p class="m-top-sm m-bottom-sm">
                          Inspired by refined comfort and the minimalist
                          aesthetic of Scandinavian Modernism, Bodie has been
                          created to provide practical luxury in a softer space.
                          Bodie creates an enduring first impression.
                        </p>
                        <a href="./#/SinglePost " style="color: firebrick"
                          ><i class="fa fa-angle-double-right"></i> Continue
                          reading</a
                        >
                        <span
                          class="post-like text-muted tooltip-test"
                          data-toggle="tooltip"
                          data-original-title="I like this post!"
                        >
                          <i class="fa fa-heart" style="color: #e31c1c;"></i>
                          <span class="like-count">43</span>
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
                <!------------- Post2 ------------->
                <div class="card" style="  background: #fcfcfc;">
                  <div class="panel-blog-container">
                    <div class="panel-body">
                      <div class="image-wrapper">
                        <carousel
                          :per-page="1"
                          loop
                          :speed="700"
                          :autoplay-timeout="5000"
                          :mouse-drag="false"
                          navigationEnabled
                          navigationNextLabel="<i class='material-icons'>keyboard_arrow_right</i>"
                          navigationPrevLabel="<i class='material-icons'>keyboard_arrow_left</i>"
                        >
                          <slide>
                            <div class="carousel-caption"></div>
                            <img :src="carousel3" alt="carousel3" />
                          </slide>
                          <slide>
                            <div class="carousel-caption"></div>
                            <img :src="carousel4" alt="carousel4" />
                          </slide>
                        </carousel>
                      </div>
                      <div class="widget-blog-author">
                        <div class="widget-blog-author-image">
                          <img
                            src="https://th.bing.com/th/id/R.81ac444299f5b87481f37afd49227cf7?rik=6EwkKdvRW8U7hw&pid=ImgRaw&r=0"
                            alt=""
                          />
                        </div>
                      </div>
                      <h4>Meeting Room interior dedign</h4>
                      <div class="text">
                        <small class="text-muted"
                          >By <a href="#"><strong> John Doe</strong></a> | Post
                          on Dec 10, 2021 | 32 comments</small
                        >
                        <p class="m-top-sm m-bottom-sm">
                          Our Office Collection was created for the new way we
                          live and work,providing beautify designed, ergonomic,
                          and sustainably made furniture for the home. Designed
                          by john doe and engineered by Home Furniture Design’s
                          expert team, it is an elegant, fluid table that sits
                          stylishly in any space.The luxuriously soft padding
                          adds extra comfort, while its fine seam patterned
                          upholstery and striking sleek chrome arms demonstrate
                          the refined detail we strive for. The polished
                          aluminum 4-star swivel base and glides for hard or
                          soft floors.
                          <a href="./#/SinglePost" style="color: firebrick">
                            <i class="fa fa-angle-double-right"></i>
                            Continue reading</a
                          >
                          <span
                            class="post-like text-muted tooltip-test"
                            data-toggle="tooltip"
                            data-original-title="I like this post!"
                          >
                            <i class="fa fa-heart" style="color: #e31c1c;"></i>
                            <span class="like-count">68</span>
                          </span>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <!------------- Post3 ------------->
                <div class="card" style="  background: #fcfcfc;">
                  <div class="panel-blog-container">
                    <div class="panel-body">
                      <div class="image-wrapper">
                        <img
                          src="https://images.pexels.com/photos/7045920/pexels-photo-7045920.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                          alt=""
                        />
                      </div>
                      <div class="widget-blog-author">
                        <div class="widget-blog-author-image">
                          <img
                            src="https://taylor.tulane.edu/wp-content/uploads/2018/08/myron-e1535568315324.png"
                            alt=""
                          />
                        </div>
                      </div>
                      <h4>Fairfax Living Room</h4>
                      <div class="text">
                        <small class="text-muted"
                          >By <a href="#"><strong> Devid lio</strong></a> | Post
                          on Oct 30, 2021 | 58 comments</small
                        >
                        <p class="m-top-sm m-bottom-sm">
                          The Fairfax collection has a confident and
                          contemporary aesthetic. The elegant low back design,
                          linear form and deep buttoned, tapered seat cushion,
                          delivers a refined range with an impressive level of
                          comfort. The elegant low back design, linear form and
                          deep buttoned, tapered seat cushion, delivers a
                          refined range with an impressive level of comfort. The
                          armchair, two and three seat sofas have delightful
                          attention to detail with luxurious upholstery that
                          would enhance any space.
                        </p>
                        <a href="./#/SinglePost" style="color: firebrick">
                          <i class="fa fa-angle-double-right"></i>
                          Continue reading</a
                        >
                        <span
                          class="post-like text-muted tooltip-test"
                          data-toggle="tooltip"
                          data-original-title="I like this post!"
                        >
                          <i class="fa fa-heart" style="color: #e31c1c;"></i>
                          <span class="like-count">25</span>
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
                <!------------- Post4 ------------->
                <div class="card" style="  background: #fcfcfc;">
                  <div class="panel-blog-container">
                    <div class="panel-body">
                      <div class="image-wrapper">
                        <carousel
                          :per-page="1"
                          loop
                          :speed="700"
                          :autoplay-timeout="5000"
                          :mouse-drag="false"
                          navigationEnabled
                          navigationNextLabel="<i class='material-icons'>keyboard_arrow_right</i>"
                          navigationPrevLabel="<i class='material-icons'>keyboard_arrow_left</i>"
                        >
                          <slide>
                            <div class="carousel-caption"></div>
                            <img :src="carousel5" alt="carousel5" />
                          </slide>
                          <slide>
                            <div class="carousel-caption"></div>
                            <img :src="carousel6" alt="carousel6" />
                          </slide>
                        </carousel>
                      </div>
                      <div class="widget-blog-author">
                        <div class="widget-blog-author-image">
                          <img
                            :src="img"
                            style="width:60px;height:60px"
                            alt=""
                          />
                        </div>
                      </div>
                      <h4>WOODEN DISH</h4>
                      <div class="text">
                        <small class="text-muted"
                          >By
                          <a href="#"><strong> Abdelrahman Ezzet</strong></a> |
                          Post on February 1, 2021 | 33 comments</small
                        >
                        <p class="m-top-sm m-bottom-sm">
                          This versatile offering is ideally suited to the home,
                          perfect for an office, dining and lounge environment.
                          To achieve the comfort levels for there is a generous
                          scoop to the seat, whilst the lounge chair offers a
                          slight back recline. An incredibly hard-wearing and
                          robust construction finished in Black American Walnut
                          or European Oak, complimented by fine fabric
                          upholstery in a range of colours.
                        </p>
                        <a href="./#/SinglePost" style="color: firebrick">
                          <i class="fa fa-angle-double-right"></i>
                          Continue reading</a
                        >
                        <span
                          class="post-like text-muted tooltip-test"
                          data-toggle="tooltip"
                          data-original-title="I like this post!"
                        >
                          <i class="fa fa-heart" style="color: #e31c1c;"></i>
                          <span class="like-count">47</span>
                        </span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!-- -------------------Right Sidebar---------------------- -->
              <div
                class="col-lg-8 col-md-12 right-box"
                style="padding: 0% 1%; width:25%;"
              >
                <div class="card1">
                  <!------------- Search ------------->
                  <div class="body search">
                    <div class="search-container">
                      <form action="">
                        <button type="submit">
                          <i class="fa fa-search"></i>
                        </button>
                        <input
                          type="text"
                          placeholder="Search..."
                          name="search"
                          style="padding: 5px 12px;font-size: medium;"
                        />
                      </form>
                    </div>
                  </div>
                </div>
                <!-------------Categories Cloud------------->
                <div class="card1">
                  <h4
                    class="headline text-muted"
                    style="margin: 10px 15px;font-weight: 900;text-align: unset;"
                  >
                    Categories Clouds
                  </h4>
                  <div class="body widget" style="padding:0%">
                    <ul class="list-unstyled categories-clouds m-b-0">
                      <li>
                        <a
                          href="javascript:void(0);"
                          style="color: cornflowerblue;"
                          >Modern</a
                        >
                      </li>
                      <li>
                        <a
                          href="javascript:void(0);"
                          style="color: cornflowerblue;"
                          >Classic</a
                        >
                      </li>
                      <li>
                        <a
                          href="javascript:void(0);"
                          style="color: cornflowerblue;"
                          >Livingroom</a
                        >
                      </li>
                      <li>
                        <a
                          href="javascript:void(0);"
                          style="color: cornflowerblue;"
                          >Bedroom</a
                        >
                      </li>
                      <li>
                        <a
                          href="javascript:void(0);"
                          style="color: cornflowerblue;"
                          >Officeroom</a
                        >
                      </li>
                    </ul>
                  </div>
                </div>
                <!-------------Popular Post------------->
                <div class="card1">
                  <h4 class="headline text-muted">
                    POPULAR POST
                  </h4>
                  <div class="media-popular-post">
                    <a class="" href="#">
                      <center>
                        <img
                          width="150"
                          height="150"
                          src="https://images.pexels.com/photos/271676/pexels-photo-271676.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                          alt="Popular Post"
                          style="padding-bottom: 5%;"
                        />
                      </center>
                    </a>
                    <div class="media-body" style="text-align: center;">
                      I design to make women feel confident and fashion.
                    </div>
                  </div>

                  <div class="media-popular-post">
                    <a class="pull-left" href="#">
                      <img
                        width="60"
                        height="60"
                        src="https://images.pexels.com/photos/6284238/pexels-photo-6284238.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260"
                        alt="Popular Post"
                      />
                    </a>
                    <div class="media-body">
                      My inspiration for interior design is more historical than
                      traditional
                    </div>
                  </div>

                  <div class="media-popular-post">
                    <a class="pull-left" href="#">
                      <img
                        width="60"
                        height="60"
                        src="https://images.pexels.com/photos/4635231/pexels-photo-4635231.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                        alt="Popular Post"
                      />
                    </a>
                    <div class="media-body">
                      Recognizing the need is the primary condition for design
                    </div>
                  </div>

                  <div class="media-popular-post">
                    <a class="pull-left" href="#">
                      <img
                        width="60"
                        height="60"
                        src="https://images.pexels.com/photos/276534/pexels-photo-276534.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
                        alt="Popular Post"
                      />
                    </a>
                    <div class="media-body">
                      Best accessories to add into your wardrobe summer
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- --------------------Pagination------------------------- -->
          <ul
            class="pagination pagination-primary"
            style=" margin-left: auto; margin-right: auto; width: 60%;"
          >
            <li class="page-item">
              <a class="page-link" href="javascript:void(0);">Previous</a>
            </li>
            <li class="page-item active">
              <a
                class="page-link"
                href="javascript:void(0);"
                style="background-color: black;"
                >1</a
              >
            </li>
            <li class="page-item">
              <a class="page-link" href="javascript:void(0);">2</a>
            </li>
            <li class="page-item">
              <a class="page-link" href="javascript:void(0);">3</a>
            </li>
            <li class="page-item">
              <a class="page-link" href="javascript:void(0);">4</a>
            </li>
            <li class="page-item">
              <a class="page-link" href="javascript:void(0);">....</a>
            </li>
            <li class="page-item">
              <a class="page-link" href="javascript:void(0);">Next</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  name: "post",
  bodyClass: "post-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/leaf7.jpg"),
    },
    img: {
      type: String,
      default: require("@/assets/img/00.jpg"),
    },
  },
  data() {
    return {
      carousel1: require("@/assets/img/c1.jpeg"),
      carousel2: require("@/assets/img/c2.jpeg"),
      carousel3: require("@/assets/img/c3.jpg"),
      carousel4: require("@/assets/img/c4.jpg"),
      carousel5: require("@/assets/img/blog-details-img25.jpg"),
      carousel6: require("@/assets/img/blog-details-img26.jpg"),
      list: [],
    };
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

<style lang="scss" scoped>
.post-like {
  float: right;
  cursor: pointer;
}

/*Popular Post*/
.headline {
  margin: 20px 0;
  font-weight: 500;
  text-align: center;
}

.media,
.media-body {
  overflow: hidden;
  zoom: 1;
}
/*Body*/
.row {
  width: 100%;
}

.text {
  padding-left: 2%;
}

.media-body {
  text-align: inherit;
  font-size: small;
  padding-left: inherit;
}

.media-popular-post {
  padding: 5%;
}

.panel-blog-container {
  padding-bottom: 3%;
  padding-right: 3%;
}
strong {
  color: cornflowerblue;
}

/*Profile Picture*/
.widget-blog-author-image {
  float: left;
  margin-top: -30px;
  padding: 5px;
  border-radius: 70px;
  width: 70px;
  height: 70px;
  background: #fff;
  position: relative;
}

.widget-blog-author-image img {
  max-width: 100%;
  border-radius: 70px;
}

/* Right Box Card */
.card {
  border: 0;
  margin-bottom: 5%;
  border-radius: 0.55rem;
  position: relative;
  width: 100%;
  box-shadow: 0 1px 2px 0 rgb(0 0 0 / 25%);
}
.card .body {
  color: #444;
  padding: 6%;
  font-weight: 500;
}

.right-box .categories-clouds li {
  display: inline-block;
  margin-bottom: 5px;
  margin-left: 3px;
}

.right-box .categories-clouds li a {
  display: block;
  border: 1px solid;
  padding: 8px 7px;
  border-radius: 3px;
  margin: 1px;
}

.card1 {
  background: white;
  border: 1px solid #e8e8e8;
  margin-bottom: 10%;
  background-color: #fff;
}
.card1 .body {
  color: #444;
  padding: 6%;
  font-weight: 500;
}
/* Search */
.search-container form {
  position: relative;
}

.search-container form button {
  position: absolute;
  right: 0;
  top: 0;
  height: 100%;
  width: 50px;
  background: transparent;
  border: transparent;
  font-size: 20px;
  color: #4b00ff;
  cursor: pointer;
}
</style>
