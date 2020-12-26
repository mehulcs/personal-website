<template>
  <v-app>
    <v-content>
      <v-layout row justify-center align-center fill-height>
        <v-flex xs11 sm7 md5 lg3 py-3>
          <v-card elevation="4">
            <v-layout column wrap>
              <v-flex py-3>
                <v-layout justify-center>
                  <img
                    src="./assets/mehulprajapati.jpg"
                    width="150"
                    height="150"
                    style="border-radius:100%;border:3px solid rgb(100, 112, 167);"
                    alt="Mehul Prajapati"
                  >
                </v-layout>
              </v-flex>
              <v-flex px-4>
                <v-layout column wrap>
                  <v-flex>
                    <v-layout column align-center>
                      <span class="display-1">Mehul Prajapati</span>
                      <span class="subheading" style="color:rgb(100, 112, 167);">Software Engineer</span>
                    </v-layout>
                  </v-flex>
                  <v-flex mt-3>
                    <span>I'm a Software Engineer from India and this is my personal website. I'm pretty good at full-stack development and I have a keen interest in AI/ML and Data Science applications.</span>
                  </v-flex>
                  <v-divider class="mt-4"></v-divider>
                  <v-flex mt-3>
                    <v-layout row wrap>
                      <v-flex xs12 sm6>
                        <v-layout column>
                          <v-flex>
                            <v-layout align-center>
                              <v-icon>phone</v-icon>
                              <a href="tel:+919738901021">
                                <span class="ml-2">+91 9738901021</span>
                              </a>
                            </v-layout>
                          </v-flex>
                          <v-flex mt-1>
                            <v-layout align-center>
                              <v-icon>email</v-icon>
                              <a href="mailto:mehul.becs@gmail.com">
                                <span class="ml-2">mehul.becs@gmail.com</span>
                              </a>
                            </v-layout>
                          </v-flex>
                        </v-layout>
                      </v-flex>
                      <v-flex xs12 sm6>
                        <v-divider class="my-3 hidden-sm-and-up"></v-divider>
                        <v-layout column align-center justify-center>
                          <v-icon color="rgb(100, 112, 167)">location_on</v-icon>
                          <span class="mt-1">Bengaluru, India</span>
                        </v-layout>
                      </v-flex>
                    </v-layout>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex mt-4 py-2>
                <v-layout row justify-center align-center>
                  <v-flex shrink mr-2>
                    <a href="https://medium.com/@mehulcs" target="_blank">
                      <i class="fab fa-lg fa-medium" style="color: rgb(100, 112, 167);" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                  <v-flex shrink mr-2>
                    <a href="https://www.linkedin.com/in/mehulcs" target="_blank">
                      <i class="fab fa-lg fa-linkedin" style="color: rgb(100, 112, 167);" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                  <v-flex shrink mr-2>
                    <a href="https://twitter.com/mehul_cs" target="_blank">
                      <i class="fab fa-lg fa-twitter-square" style="color: rgb(100, 112, 167);" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                  <v-flex shrink>
                    <a href="https://github.com/mehulcs" target="_blank">
                      <i class="fab fa-lg fa-github" style="color: rgb(100, 112, 167);" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                </v-layout>
              </v-flex>
            </v-layout>
          </v-card>
        </v-flex>
      </v-layout>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      //
    };
  }
};
</script>
