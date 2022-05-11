<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            <div class="brand">
              <div class="shoptitle"></div>
              <h1 class="shopmain">Post</h1>
              <h3 class="shopmain"></h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
    <!-- ----------------------------- -->
    <div class="main main-raised">
      <div class="section section-basic">
        <div class="container">
          <div class="container bootstrap snippets bootdey">
            <div class="row">
              <!-- Post1 -->
              <div
                class="col-lg-8 col-md-12 left-box"
                style="width: 75%; padding: 0% 3%;"
              >
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

                    <h3 style="font-weight: 400;">SÖDERHAMN Living Room</h3>

                    <div class="text">
                      <p class="m-top-sm m-bottom-sm">
                        Inspired by refined comfort and the minimalist aesthetic
                        of Scandinavian Modernism, Bodie has been created to
                        provide practical luxury in a softer space. Bodie
                        creates an enduring first impression. Characterised by
                        the smooth curve of the sofa’s cushions, which
                        seamlessly combines a strong structure with a simple,
                        organic expression. Appearing compact and neat within
                        space, yet spacious and with generous comfort.
                      </p>
                      <p class="m-top-sm m-bottom-sm">
                        “People are migrating away from their desks looking for
                        kinds of spaces that they feel comfortable in. We wanted
                        to disrupt the mediocre with an encounter that will
                        provide a quality experience.” Tom Potts Furniture
                        Designer. <br />
                        Designed, crafted and stitched by our master craftsmen
                        in Cheltenham; Bodie is the perfect choice for spaces
                        where low maintenance and high comfort is required with
                        an exquisite attention to detail.
                      </p>
                      <span
                        class="post-like text-muted tooltip-test"
                        data-toggle="tooltip"
                        data-original-title="I like this post!"
                      >
                      </span>
                    </div>

                    <!-- Post2 -->
                    <br />
                    <div class="row" style="">
                      <div class="col-sm-8" style="padding-right: 3%;">
                        <img
                          src="https://hongo.b-cdn.net/furniture/wp-content/uploads/sites/4/2018/09/blog-details-img20.jpg.webp"
                          alt="Popular Post"
                        />
                      </div>
                      <div class="col-sm-4" style="width:103%">
                        <div class="col-sm">
                          <img
                            src="https://hongo.b-cdn.net/furniture/wp-content/uploads/sites/4/2018/09/blog-details-img21.jpg.webp"
                            alt="Popular Post"
                          />
                        </div>
                        <div class="col-sm">
                          <h5 style="font-weight:500">
                            The interior of the house personifies the private
                            world the exterior of it is part of the outside
                            world
                          </h5>
                          <p>
                            Interior design is all about how we experience
                            spaces. It’s a powerful, essential part of our daily
                            lives and affects how we live, work, play, and even
                            heal. Comfortable homes, functional workplaces,
                            beautiful public spaces—that’s interior design at
                            work.
                          </p>
                        </div>
                      </div>
                    </div>

                    <br />
                    <hr />

                    <!-- Comments -->
                    <div class="header" style="padding-top:3%">
                      <h3 style="font-weight: 500;text-align: center;">
                        Comments
                      </h3>
                    </div>
                    <div class="body">
                      <ul class="comment-reply list-unstyled">
                        <!-- First comment -->
                        <li class="row clearfix">
                          <div
                            class="md-layout-item md-size-10 md-xsmall-size-50 ml-auto"
                          >
                            <img
                              class="img-fluid img-thumbnail"
                              src="https://bootdey.com/img/Content/avatar/avatar7.png"
                              alt="Awesome Image"
                            />
                          </div>
                          <div class="text-box col-md-10 col-8 p-l-0 p-r0">
                            <a href="#/Profile"
                              ><h5 class="m-b-0">Gems Nekil</h5></a
                            >
                            <p>
                              Why are there so many tutorials on how to decouple
                              WordPress? how fast and easy it is to get it
                              running (and keep it running!) and its massive
                              ecosystem.
                            </p>
                            <ul class="list-inline">
                              <li>
                                <a href="javascript:void(0);">Mar 09 2021</a>
                              </li>
                              <li><a href="javascript:void(0);">Reply</a></li>
                            </ul>
                          </div>
                        </li>
                        <!-- Second comment -->
                        <li class="row clearfix">
                          <div
                            class="md-layout-item md-size-10 md-xsmall-size-50 ml-auto"
                          >
                            <img
                              class="img-fluid img-thumbnail"
                              src="https://bootdey.com/img/Content/avatar/avatar3.png"
                              alt="Awesome Image"
                            />
                          </div>
                          <div class="text-box col-md-10 col-8 p-l-0 p-r0">
                            <a href="#/Profile"
                              ><h5 class="m-b-0">Gigi Hadid</h5></a
                            >
                            <p>
                              Why are there so many tutorials on how to decouple
                              WordPress? how fast and easy it is to get it
                              running (and keep it running!) and its massive
                              ecosystem.
                            </p>
                            <ul class="list-inline">
                              <li>
                                <a href="javascript:void(0);">Oct 30 2020</a>
                              </li>
                              <li><a href="javascript:void(0);">Reply</a></li>
                            </ul>
                          </div>
                        </li>
                        <li class="row clearfix">
                          <div
                            class="md-layout-item md-size-10 md-xsmall-size-50 ml-auto"
                          >
                            <img
                              class="img-fluid img-thumbnail"
                              src="https://bootdey.com/img/Content/avatar/avatar4.png"
                              alt="Awesome Image"
                            />
                          </div>
                          <div class="text-box col-md-10 col-8 p-l-0 p-r0">
                            <a href="#/Profile">
                              <h5 class="m-b-0">Tony Marko</h5></a
                            >
                            <p>
                              Very nice and informative article. In all the
                              years I've done small and side-projects as a
                              freelancer, I've ran into a few problems here and
                              there.
                            </p>
                            <ul class="list-inline">
                              <li>
                                <a href="javascript:void(0);">Jun 20 2022</a>
                              </li>
                              <li><a href="javascript:void(0);">Reply</a></li>
                            </ul>
                          </div>
                        </li>
                      </ul>
                    </div>

                    <!-- Add Comment -->
                    <md-field maxlength="5">
                      <label>Your Comment</label>
                      <md-textarea v-model="message"></md-textarea>
                    </md-field>
                    <div class="md-layout">
                      <div
                        class="md-layout-item md-size-33 mx-auto text-center"
                      >
                        <md-button class="md-primary">Send Comment</md-button>
                      </div>
                    </div>

                    <!-- Profile Card -->
                    <div
                      class="card1"
                      style="margin-top: 10%;    margin-bottom: 7%;"
                    >
                      <div class="row" style="    padding: 2% 5%;">
                        <div class="col-sm-3" style="width:15%">
                          <img
                            :src="img"
                            alt="Circle Image"
                            class="rounded-circle"
                            style=""
                          />
                        </div>
                        <div class="col-sm-9">
                          <div class="detail" style="    padding: 0% 3%;">
                            <h6 style="font-weight: 700;">
                              Abdelrahman Ezzat
                            </h6>
                            <p>
                              There is no passion to be found playing small in
                              settling for a life that is less than the one you
                              are capable of living.
                            </p>
                          </div>
                        </div>
                      </div>
                      <div
                        class="md-layout-item md-size-30 mx-auto"
                        style="padding-left: 10%;"
                      >
                        <md-button class="" style="width: 90%"
                          >All Author Posts</md-button
                        >
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!-- SideBar -->
              <div
                class="col-lg-8 col-md-12 right-box"
                style="padding: 0% 1%; width:25%;"
              >
                <div class="card1">
                  <div class="md-layout">
                    <div class="md-layout-item">
                      <h5 style="text-align: center; font-weight: 500">
                        About me
                      </h5>
                      <a href="#/profile" target="_blank">
                        <center>
                          <img
                            width="50%"
                            :src="img"
                            alt="Circle Image"
                            class="rounded-circle"
                            style="padding: 4% 4%;"
                          />
                        </center>
                      </a>
                      <h5 style="text-align: center;">Abdelrahman Ezzet</h5>
                      <p style="text-align: center; padding: 5% 8%;">
                        Welcome to everyday my lifestyle <br />
                        I'm Abdo designer & engineering.
                      </p>

                      <!-- Social icon -->
                      <div
                        class="social-icon"
                        style="float:left; padding: 2% 17%"
                      >
                        <md-list-item
                          style="float:left"
                          href="https://twitter.com/CreativeTim"
                          target="_blank"
                        >
                          <i class="fab fa-twitter"></i>
                          <p class="hidden-lg">Twitter</p>
                          <md-tooltip md-direction="bottom"
                            >Follow us on Twitter</md-tooltip
                          >
                        </md-list-item>
                        <md-list-item
                          style="float:inherit"
                          href="https://www.facebook.com/CreativeTim"
                          target="_blank"
                        >
                          <i class="fab fa-facebook-square"></i>
                          <p class="hidden-lg">Facebook</p>
                          <md-tooltip md-direction="bottom"
                            >Like us on Facebook</md-tooltip
                          >
                        </md-list-item>
                        <md-list-item
                          style="float:inherit;"
                          href="https://www.instagram.com/CreativeTimOfficial"
                          target="_blank"
                        >
                          <i class="fab fa-instagram"></i>
                          <p class="hidden-lg">Instagram</p>
                          <md-tooltip md-direction="bottom"
                            >Follow us on Instagram</md-tooltip
                          >
                        </md-list-item>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Related Post -->
        <div class="container" style="text-align: center;">
          <h4 style="font-weight: bold">Related Post</h4>
          <div class="team">
            <div class="md-layout">
              <!-- Card1 -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout md-size-50 mx-auto">
                      <div class="hovereffect">
                        <a href="#/Post">
                          <img
                            src="https://images.unsplash.com/photo-1617103996702-96ff29b1c467?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1032&q=80"
                            alt=""
                            class=""
                          />
                        </a>
                      </div>
                    </div>
                    <div class="card1">
                      <h4 style="font-weight:400">
                        SÖDERHAMN Sofas
                      </h4>
                      <md-card-content>
                        <p class="card-description">
                          Armchairs and chaise lounges with a sleek and modular
                          design that you can combine in many ways
                        </p>
                      </md-card-content>
                    </div>
                  </md-card>
                </div>
              </div>

              <!-- Card2 -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout md-size-50 mx-auto">
                      <div class="hovereffect">
                        <a href="#/Post">
                          <img
                            src="https://images.unsplash.com/photo-1618221381711-42ca8ab6e908?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1032&q=80"
                            alt=""
                            class=""
                          />
                        </a>
                      </div>
                    </div>

                    <!-- Card3 -->
                    <div class="card1">
                      <h4 style="font-weight:400">PÄRUP Sleek design</h4>
                      <md-card-content>
                        <p class="card-description">
                          Quick assembly and easy to care for, including a
                          compact sofa-bed that is perfect for small spaces
                        </p>
                      </md-card-content>
                    </div>
                  </md-card>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout md-size-50 mx-auto">
                      <div class="hovereffect">
                        <a href="#/Post">
                          <img
                            src="https://images.unsplash.com/photo-1618221469555-7f3ad97540d6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1032&q=80"
                            alt="Thumbnail Image"
                            class=""
                          />
                        </a>
                      </div>
                    </div>
                    <div class="card1">
                      <h4 style="font-weight:400">
                        ÄPPLARYD sofa
                      </h4>
                      <md-card-content>
                        <p class="card-description">
                          Say hello to the ÄPPLARYD sofa: Sleek lines, spacious
                          seats for reclining modern design. What’s not to love?
                        </p>
                      </md-card-content>
                    </div>
                  </md-card>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  name: "singlepost",
  bodyClass: "singlepost-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/postdetail.jpg"),
    },
    img: {
      type: String,
      default: require("@/assets/img/abdo.jpg"),
    },
  },
  data() {
    return {
      carousel1: require("@/assets/img/c1.jpeg"),
      carousel2: require("@/assets/img/c2.jpeg"),
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
.row {
  width: 100%;
}

.headline {
  margin: 2% 0;
  font-weight: 500;
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
// --------------------------------
.clearfix {
  padding: 0% 0% 1%;
}
.comment-reply li h5 {
  font-size: 18px;
}

.comment-reply .list-inline li {
  display: inline-block;
  margin: 0;
  padding-right: 20px;
}

.comment-reply .list-inline li a {
  font-size: 13px;
}
</style>
