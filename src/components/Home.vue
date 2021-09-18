<template>
  <v-container class="fill-height">
    <v-row align="center" class="text-center" style="height: 100vh;">
      <v-col cols="12" style="position: absolute; top: calc(100vh - 64px); width: 100%; left: 0px;">
        <div class="mb-5">
          <v-icon class="pb-1 mr-1">mdi-console</v-icon>
          A Fullstack Developer, currently focusing on Angular, React, Vue, NodeJS and .NET Technologies
        </div>
      </v-col>
      <v-col cols="12">
        <h1 class="display-3 font-weight-bold mb-5">
          <span class="text-primary">
            Basilius Bias Astho Christyono
          </span>
        </h1>
        <v-divider></v-divider>
        <h2 class="subheading font-weight-regular mt-5">
          <v-icon class="pb-1 mr-1">mdi-briefcase-outline</v-icon>
          Software Engineer
          <v-icon class="pb-1 my-1">mdi-map-marker-outline</v-icon>
          Jakarta, Indonesia
        </h2>
      </v-col>
    </v-row>
    <v-row align="center" class="my-5">
      <v-col cols="12">
        <v-card>
            <v-row class="ma-0">
              <v-col cols="12" sm="5">
                <v-img class="ma-5" src="../assets/photo.png" ></v-img>
              </v-col>
              <v-col cols="12" sm="7">
                <v-card-title>
                  <h3 class="display-1 font-weight-bold mb-3">
                    About Me
                  </h3>
                </v-card-title>
                <v-card-subtitle>
                  <h3 class="subheading font-weight-regular my-3">
                    ✨ Villagers who are interested in technological developments~ <br />
                    📌 Interest in <b>software</b>, <b>web</b>, <b>data mining</b>, and <b>distributed systems</b> &amp; <b>networks</b>
                  </h3>
                  <v-row class="my-3">
                    <v-col cols="12" sm="6">
                      <v-row>
                        <v-col cols="12">
                          <h2 class="subheading font-weight-bold mt-3">
                            Frontend
                          </h2>
                        </v-col>
                        <v-col cols="12 py-0 px-3">
                          <v-btn icon x-large>
                            <v-icon>mdi-angular</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-react</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-vuejs</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-android</v-icon>
                          </v-btn>
                        </v-col>
                      </v-row>
                      <v-row>
                        <v-col cols="12">
                          <h2 class="subheading font-weight-bold mt-3">
                            Backend
                          </h2>
                        </v-col>
                        <v-col cols="12 py-0 px-3">
                          <v-btn icon x-large>
                            <v-icon>mdi-nodejs</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-dot-net</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-laravel</v-icon>
                          </v-btn>
                        </v-col>
                      </v-row>
                    </v-col>
                    <v-col cols="12" sm="6">
                      <v-row>
                        <v-col cols="12">
                          <h2 class="subheading font-weight-bold mt-3">
                            Clouds
                          </h2>
                        </v-col>
                        <v-col cols="12 py-0 px-3">
                          <v-btn icon x-large>
                            <v-icon>mdi-aws</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-google-cloud</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-digital-ocean</v-icon>
                          </v-btn>
                        </v-col>
                      </v-row>
                      <v-row>
                        <v-col cols="12">
                          <h2 class="subheading font-weight-bold mt-3">
                            Others
                          </h2>
                        </v-col>
                        <v-col cols="12 py-0 px-3">
                          <v-btn icon x-large>
                            <v-icon>mdi-language-html5</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-css3</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-javascript</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-typescript</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-csharp</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-php</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-python</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-java</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-c</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-cpp</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-kotlin</v-icon>
                          </v-btn>
                          <v-btn icon x-large>
                            <v-icon>mdi-language-go</v-icon>
                          </v-btn>
                        </v-col>
                      </v-row>
                    </v-col>
                  </v-row>
                </v-card-subtitle>
              </v-col>
            </v-row>
          </v-card>
      </v-col>
    </v-row>
    <v-row align="center" class="text-center mb-5">
      <v-col cols="12">
        <span class="text-primary"> ~ So Bad Yet, So Good! (｡&gt;﹏&lt;｡) ~ </span>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'Home',
    data: () => ({
      portfolio: [
        {
          title: 'Content Title',
          description: 'Content Description',
          type: 'Open Source',
          images: [
            'https://via.placeholder.com/256?text=1',
            'https://via.placeholder.com/256?text=2',
            'https://via.placeholder.com/256?text=3',
            'https://via.placeholder.com/256?text=4'
          ],
        }
      ]
    }),
  }
</script>
