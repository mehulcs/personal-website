<template>
  <v-app>
    <v-content>
      <v-layout row justify-center align-center fill-height>
        <v-flex xs11 sm7 md5 lg3 py-3>
          <v-card elevation="4">
            <v-layout column wrap>
              <v-flex py-3 style="background:linear-gradient(#7986CB 70%, white 30%);">
                <v-layout justify-center>
                  <img
                    src="./assets/mehulprajapati.jpeg"
                    width="150"
                    height="150"
                    style="border-radius:100%;border:3px solid #7986CB;"
                    alt="Mehul Prajapati"
                  >
                </v-layout>
              </v-flex>
              <v-flex px-4>
                <v-layout column wrap>
                  <v-flex>
                    <v-layout column align-center>
                      <span class="display-1">Mehul Prajapati</span>
                      <span class="subheading" style="color:#7986CB;">Software Engineer</span>
                    </v-layout>
                  </v-flex>
                  <v-flex mt-3>
                    <span>I'm software engineer with experience of full stack and blockchain applications development. I write articles on JavaScript and other technologies.</span>
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
                          <v-icon color="#7986CB">location_on</v-icon>
                          <span class="mt-1">Bengaluru, India</span>
                        </v-layout>
                      </v-flex>
                    </v-layout>
                  </v-flex>
                </v-layout>
              </v-flex>
              <v-flex mt-4 py-2 style="background-color:#7986CB;">
                <v-layout row justify-center align-center>
                  <v-flex shrink mr-2>
                    <a href="https://medium.com/@mehulcs">
                      <i class="fab fa-lg fa-medium white--text" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                  <v-flex shrink mr-2>
                    <a href="https://www.linkedin.com/in/mehulcs">
                      <i class="fab fa-lg fa-linkedin white--text" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                  <v-flex shrink mr-2>
                    <a href="https://twitter.com/mehul_cs">
                      <i class="fab fa-lg fa-twitter-square white--text" aria-hidden="true"></i>
                    </a>
                  </v-flex>
                  <v-flex shrink>
                    <a href="https://github.com/mehulcs">
                      <i class="fab fa-lg fa-github white--text" aria-hidden="true"></i>
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
