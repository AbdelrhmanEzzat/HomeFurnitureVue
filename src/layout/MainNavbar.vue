<template>
  <md-toolbar
    id="toolbar"
    md-elevation="0"
    class="md-transparent md-absolute"
    :class="extraNavClasses"
    :color-on-scroll="colorOnScroll"
  >
    <div class="md-toolbar-row md-collapse-lateral">
      <div class="md-toolbar-section-start">
        <a href="/#/home"><h1 class="md-title">Home Furniture</h1></a>
      </div>
      <div class="md-toolbar-section-end">
        <md-button
          class="md-just-icon md-simple md-toolbar-toggle"
          :class="{ toggled: toggledClass }"
          @click="toggleNavbarMobile()"
        >
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </md-button>

        <div class="md-collapse">
          <div class="md-collapse-wrapper">
            <mobile-menu nav-mobile-section-start="false">
              <!-- Here you can add your items from the section-start of your toolbar -->
            </mobile-menu>
            <md-list>
              <!-- <li class="md-list-item" v-if="!showDownload">
                <a
                  href="javascript:void(0)"
                  class="md-list-item-router md-list-item-container md-button-clean dropdown"
                >
                  <div class="md-list-item-content">
                    <drop-down direction="down">
                      <md-button
                        slot="title"
                        class="md-button md-button-link md-white md-simple dropdown-toggle"
                        data-toggle="dropdown"
                      >
                        <i class="material-icons">apps</i>
                        <p>Components</p>
                      </md-button>
                      <ul class="dropdown-menu dropdown-with-icons">
                        <li>
                          <a href="#/">
                            <i class="material-icons">layers</i>
                            <p>All Components</p>
                          </a>
                        </li>
                        <li>
                          <a
                            href="https://demos.creative-tim.com/vue-material-kit/documentation/"
                          >
                            <i class="material-icons">content_paste</i>
                            <p>Documentation</p>
                          </a>
                        </li>
                      </ul>
                    </drop-down>
                  </div>
                </a>
              </li> -->

              <md-list-item
                href="/#/home"
                @click="scrollToElement()"
                v-if="showDownload"
              >
                <i class="material-icons">home</i>
                <p>Home</p>
              </md-list-item>

              <md-list-item
                href="/#/shop"
                @click="scrollToElement()"
                v-if="showDownload"
              >
                <i class="material-icons">store</i>
                <p>Shop</p>

              </md-list-item>
              <li class="md-list-item">
                <a
                  href="javascript:void(0)"
                  class="md-list-item-router md-list-item-container md-button-clean dropdown"
                >
                  <div class="md-list-item-content">
                    <drop-down direction="down" class="profile-photo">
                    
                      <ul class="dropdown-menu dropdown-menu-right">
                        <li class="dropdown-header">Categories</li>
                        <li>
                          <a href="/#/chair" class="dropdown-item">Chair</a>
                        </li>
                        
                          <li>
                          <a href="javascript:void(0" class="dropdown-item">Tables</a>
                        </li>
                        
                        <li>
                          <a href="javascript:void(0)" class="dropdown-item">Loung</a>
                        </li>
                      </ul>
                    </drop-down>
                  </div>
                </a>
              </li>

              <md-list-item
                href="/#/post"
                @click="scrollToElement()"
                v-if="showDownload"
              >
                <i class="material-icons">content_paste</i>
                <p>Post</p>
              </md-list-item>

              <md-list-item
                href="/#/login"
                @click="scrollToElement()"
                v-if="showDownload"
              >
                <i class="material-icons">login</i>
                <p>login</p>
              </md-list-item>

              <!-- <li class="md-list-item" v-else>
                <a
                  href="javascript:void(0)"
                  class="md-list-item-router md-list-item-container md-button-clean dropdown"
                >
                  <div class="md-list-item-content">
                    <drop-down direction="down">
                      <md-button
                        slot="title"
                        class="md-button md-button-link md-white md-simple dropdown-toggle"
                        data-toggle="dropdown"
                      >
                        <i class="material-icons">view_carousel</i>
                        <p>Examples</p>
                      </md-button>
                      <ul class="dropdown-menu dropdown-with-icons">
                        <li>
                          <a href="#/landing">
                            <i class="material-icons">view_day</i>
                            <p>Landing Page</p>
                          </a>
                        </li>
                        <li>
                          <a href="#/login">
                            <i class="material-icons">fingerprint</i>
                            <p>Login Page</p>
                          </a>
                        </li>
                        <li>
                          <a href="#/profile">
                            <i class="material-icons">account_circle</i>
                            <p>Profile Page</p>
                          </a>
                        </li>
                      </ul>
                    </drop-down>
                  </div>
                </a>
              </li> -->

              <md-list-item
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
                href="https://www.instagram.com/CreativeTimOfficial"
                target="_blank"
              >
                <i class="fab fa-instagram"></i>
                <p class="hidden-lg">Instagram</p>
                <md-tooltip md-direction="bottom"
                  >Follow us on Instagram</md-tooltip
                >
              </md-list-item>

              <!-- for dashhh -->
              <md-list-item
                style="border-left-style: inset;border-color: white;"
              >
              </md-list-item>

              <li class="md-list-item">
                <a
                  href="javascript:void(0)"
                  class="md-list-item-router md-list-item-container md-button-clean dropdown"
                >
                  <div class="md-list-item-content">
                    <drop-down direction="down" class="profile-photo">
                      <div
                        class="profile-photo-small"
                        slot="title"
                        data-toggle="dropdown"
                      >
                        <img :src="img" alt="Circle Image" />
                      </div>
                      <ul class="dropdown-menu dropdown-menu-right">
                        <li class="dropdown-header">Account</li>
                        <li>
                          <a href="/#/profile" class="dropdown-item">Profile</a>
                        </li>
                        <!-- <li>
                                  <a href="#pablo" class="dropdown-item"
                                    >Settings and other stuff</a
                                  >
                                </li> -->
                          <li>
                          <a href="/#/chat" class="dropdown-item">Messenger</a>
                        </li>
                        
                        <li>
                          <a href="#pablo" class="dropdown-item">Sign Out</a>
                        </li>
                      </ul>
                    </drop-down>
                  </div>
                </a>
              </li>

              <md-list-item class="cart"
                href="/#/cart"
                @click="scrollToElement()"
                v-if="showDownload"
              >
                <i class="material-icons">shopping_cart</i>
                <p>Cart</p>
                <b-badge><span style="position: fixed;
                      top: -9px;
                      right: 6px;
                      padding: 3px 9px;
                    
                      border-radius:100px;
                      background: -webkit-linear-gradient(top, #FF6969 0%,#ff0000 100%);
                      box-shadow: 0 1px 2px rgba(0,0,0,.5), 0 1px 4px rgba(0,0,0,.4), 0 0 1px rgba(0,0,0,.7) inset, 0 10px 0px rgba(255,255,255,.11) inset; 
                      -webkit-background-clip: padding-box;
                      font:bold 16px/20px  sans-serif; 
                      color: white;
                      text-decoration: none;
                      text-shadow: 0 -1px 0 rgba(0,0,0,.6);
                                        
                  ">3</span></b-badge>
               
              </md-list-item>
            </md-list>
          </div>
        </div>
      </div>
    </div>
  </md-toolbar>
</template>

<script>
let resizeTimeout;
function resizeThrottler(actualResizeHandler) {
  // ignore resize events as long as an actualResizeHandler execution is in the queue
  if (!resizeTimeout) {
    resizeTimeout = setTimeout(() => {
      resizeTimeout = null;
      actualResizeHandler();

      // The actualResizeHandler will execute at a rate of 15fps
    }, 66);
  }
}

import MobileMenu from "@/layout/MobileMenu";
export default {
  components: {
    MobileMenu,
  },
  props: {
    img: {
      type: String,
      default: require("@/assets/img/abdo.jpg"),
    },
    type: {
      type: String,
      default: "white",
      validator(value) {
        return [
          "white",
          "default",
          "primary",
          "danger",
          "success",
          "warning",
          "info",
        ].includes(value);
      },
    },
    colorOnScroll: {
      type: Number,
      default: 0,
    },
  },
  data() {
    return {
      extraNavClasses: "",
      toggledClass: false,
    };
  },
  computed: {
    showDownload() {
      const excludedRoutes = [];
      return excludedRoutes.every((r) => r !== this.$route.name);
    },
  },
  methods: {
    bodyClick() {
      let bodyClick = document.getElementById("bodyClick");

      if (bodyClick === null) {
        let body = document.querySelector("body");
        let elem = document.createElement("div");
        elem.setAttribute("id", "bodyClick");
        body.appendChild(elem);

        let bodyClick = document.getElementById("bodyClick");
        bodyClick.addEventListener("click", this.toggleNavbarMobile);
      } else {
        bodyClick.remove();
      }
    },
    toggleNavbarMobile() {
      this.NavbarStore.showNavbar = !this.NavbarStore.showNavbar;
      this.toggledClass = !this.toggledClass;
      this.bodyClick();
    },
    handleScroll() {
      let scrollValue =
        document.body.scrollTop || document.documentElement.scrollTop;
      let navbarColor = document.getElementById("toolbar");
      this.currentScrollValue = scrollValue;
      if (this.colorOnScroll > 0 && scrollValue > this.colorOnScroll) {
        this.extraNavClasses = `md-${this.type}`;
        navbarColor.classList.remove("md-transparent");
      } else {
        if (this.extraNavClasses) {
          this.extraNavClasses = "";
          navbarColor.classList.add("md-transparent");
        }
      }
    },
    scrollListener() {
      resizeThrottler(this.handleScroll);
    },
    scrollToElement() {
      let element_id = document.getElementById("downloadSection");
      if (element_id) {
        element_id.scrollIntoView({ block: "end", behavior: "smooth" });
      }
    },
  },
  mounted() {
    document.addEventListener("scroll", this.scrollListener);
  },
  beforeDestroy() {
    document.removeEventListener("scroll", this.scrollListener);
  },
};
</script>
<style lang="scss" scoped>
.sr-only .span{
  border-radius: 26px;
    background-color: red;
    color: white;
    font-size: 14px;
    padding: 3px;
    margin: 5px;
}
.md-list-item-content{
margin-left: -24px;

}
</style>

<!-- position: initial;
    top: 23px;
    right: -95px;
    padding: 4px 6px;
    border-radius: 29px;
    background-color: red;
    color: white;
}-->