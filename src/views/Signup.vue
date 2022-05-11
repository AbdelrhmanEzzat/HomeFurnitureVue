<template>
  <div class="wrapper">
    <div class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">
          <div
            class="md-layout-item md-size-40 md-small-size-66 md-xsmall-size-100 md-medium-size-40 mx-auto"
          >
            <!----------------------- Button ------------------------->
            <login-card header-color="green">
              <h4 slot="title" class="card-title">SignUp</h4>
              <md-button
                slot="buttons"
                href="javascript:void(0)"
                class="md-just-icon md-simple md-white"
              >
                <i class="fab fa-facebook-square"></i>
              </md-button>
              <md-button
                slot="buttons"
                href="javascript:void(0)"
                class="md-just-icon md-simple md-white"
              >
                <i class="fab fa-twitter"></i>
              </md-button>
              <md-button
                slot="buttons"
                href="javascript:void(0)"
                class="md-just-icon md-simple md-white"
              >
                <i class="fab fa-google-plus-g"></i>
              </md-button>
              <!---------------- Tab Button -------------------->
              <div class="md-layout" slot="tabs">
                <div class="md-layout-item md-size-100 md-small-size-100">
                  <tabs
                    :tab-name="['Customer', 'Desginer']"
                    :tab-icon="['account_circle', 'architecture']"
                    plain
                    nav-pills-icons
                    color-button="normal"
                  >
                    <!-- here you can add your content for tab-content -->
                    <!----------------------- Tab-1 ------------------------>
                    <template slot="tab-pane-1">
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>face</md-icon>
                        <label>First Name...</label>
                        <md-input v-model="firstname"></md-input>
                      </md-field>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>face</md-icon>
                        <label>Last Name...</label>
                        <md-input v-model="lastname"></md-input>
                      </md-field>

                      <div class="md-form-group" slot="inputs">
                        <md-datepicker v-model="selectedDate">
                          <label>Select Birthdate</label>
                        </md-datepicker>
                      </div>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>man</md-icon>
                        <md-radio
                          style="padding-left: 10px;"
                          v-model="radio1"
                          :value="true"
                          >Male</md-radio
                        >
                         <md-icon>woman</md-icon>
                        <md-radio v-model="radio1" :value="false"
                          >Female</md-radio
                        >
                      </md-field>

                      <div class="row-address">
                    <div class="col-auto-address">
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>location_city</md-icon>
                        <label>City...</label>
                        <md-input v-model="city"></md-input>
                      </md-field>
                    </div>
                    <div class="col-auto-address">
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>location_on</md-icon>
                        <label>Region...</label>
                        <md-input v-model="region"></md-input>
                      </md-field>
                     </div>
                    </div>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>location_on</md-icon>
                        <label>Street...</label>
                        <md-input v-model="street"></md-input>
                      </md-field>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>email</md-icon>
                        <label>Email...</label>
                        <md-input v-model="email" type="email"></md-input>
                      </md-field>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>lock_outline</md-icon>
                        <label>Password...</label>
                        <md-input v-model="password" type="password"></md-input>
                      </md-field>
                    </template>
                    <!----------------------- Tab-2 ------------------------>
                    <template slot="tab-pane-2">
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>face</md-icon>
                        <label>First Name...</label>
                        <md-input v-model="firstname"></md-input>
                      </md-field>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>face</md-icon>
                        <label>Last Name...</label>
                        <md-input v-model="lastname"></md-input>
                      </md-field>

                      <div class="md-form-group" slot="inputs">
                        <md-datepicker v-model="selectedDate">
                          <label>Select Birthdate</label>
                        </md-datepicker>
                      </div>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>man</md-icon>
                        <md-radio
                          style="padding-left: 10px;"
                          v-model="radio1"
                          :value="true"
                          >Male</md-radio
                        >
                        <md-icon>woman</md-icon>
                        <md-radio v-model="radio1" :value="false"
                          >Female</md-radio
                        >
                      </md-field>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>work</md-icon>
                        <label>Job title</label>
                        <md-input v-model="city"></md-input>
                      </md-field>

                  <div class="row-address">
                    <div class="col-auto-address">
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>location_city</md-icon>
                        <label>City...</label>
                        <md-input v-model="city"></md-input>
                      </md-field>
                    </div>
                    <div class="col-auto-address">
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>location_on</md-icon>
                        <label>Region...</label>
                        <md-input v-model="region"></md-input>
                      </md-field>
                     </div>
                    </div>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>location_on</md-icon>
                        <label>Street...</label>
                        <md-input v-model="street"></md-input>
                      </md-field>
                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>email</md-icon>
                        <label>Email...</label>
                        <md-input v-model="email" type="email"></md-input>
                      </md-field>

                      <md-field class="md-form-group" slot="inputs">
                        <md-icon>lock_outline</md-icon>
                        <label>Password...</label>
                        <md-input v-model="password" type="password"></md-input>
                      </md-field>
                    </template>
                  </tabs>
                  <!------------------ Signup Button ------------------>
                  <md-button
                    slot="footer"
                    class="md-simple-2 md-success md-lg"
                    style=" display: block;margin-left: auto;margin-right: auto;width: 40%;"
                  >
                    SignUp
                  </md-button>
                </div>
              </div>
            </login-card>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { LoginCard } from "@/components";
import { Tabs } from "@/components";

export default {
  components: {
    LoginCard,
    Tabs,
  },
  bodyClass: "login-page",
  data() {
    return {
      firstname: null,
      email: null,
      password: null,
      radio1: true,
      radio2: false,
    };
  },
  props: {
    header: {
      type: String,
      default: require("@/assets/img/cov1.webp"),
    },
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`,
      };
    },
  },
};
</script>

<style lang="scss" scoped>
 .col-auto-address{
 display: inline-block;
  width: 50%;
 }
</style>




