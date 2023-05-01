<template>
  <v-container class="fill-height">
    <v-row align="center" class="text-center" style="height: 100vh;">
      <v-col cols="12" style="position: absolute; top: calc(100vh - 64px); width: 100%; left: 0px;">
        <div class="mb-5">
          <v-icon class="pb-1 mr-1">mdi-console</v-icon>
          Fullstack Dev. - Mainly :: Node, Deno & .NET
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
      <v-col cols="12" align="start">
        <h2>What I'm Doing</h2>
        <v-divider></v-divider>
      </v-col>
      <v-col cols="12" align="start">
        <v-slide-group show-arrows>
          <v-slide-item class="mx-3" v-for="w in works" :key="w.date" v-slot="{ active, toggle }">
            <v-card class="ma-3" width="512" @click="toggle">
              <v-row v-if="!active">
                <v-col cols="4">
                  <v-img :src="require(`@/assets/${w.image}`)"></v-img>
                </v-col>
                <v-col cols="8">
                  <v-card-text class="text-center px-0">
                    <p class="text-start">
                      <span>{{ w.job }}</span>
                      <span class="me-4" style="position: absolute; right: 0;">{{ w.type }}</span>
                    </p>
                    <p class="text-h5 text-primary">{{ w.company }}</p>
                    <p class="mb-0">{{ w.date }}</p>
                    <p class="mb-0">{{ w.location }}</p>
                  </v-card-text>
                </v-col>
              </v-row>
              <v-row v-if="active">
                <v-card-text class="text-start ma-4" v-if="active">
                  <h3 class="text-primary mb-5">{{ w.industry }}</h3>
                  <p class="mb-0">{{ w.description }}</p>
                </v-card-text>
              </v-row>
            </v-card>
          </v-slide-item>
        </v-slide-group>
      </v-col>
    </v-row>
    <v-row align="center" class="text-center mb-5">
      <v-col cols="12" align="start">
        <h2>Research &amp; Paper Work</h2>
        <v-divider></v-divider>
      </v-col>
      <v-col cols="12" align="start">
        <v-timeline align-top dense>
          <v-timeline-item color="pink" small v-for="p in papers" :key="p.date">
            <v-row class="pt-1 text-start">
              <v-col cols="12" sm="3">
                {{ p.publisher }} <br />
                {{ p.date }}
              </v-col>
              <v-col>
                <strong>{{ p.title }}</strong>
                <div class="text-caption mb-2">
                  {{ p.description }} <br />
                  <a :href="p.url" class="text-decoration-none">
                    {{ p.url }}
                  </a>
                </div>
                <v-avatar v-for="i in p.images" :key="i">
                  <v-img :src="i"></v-img>
                </v-avatar>
              </v-col>
            </v-row>
          </v-timeline-item>
        </v-timeline>
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
      works: [
        {
          job: '.NET Software Engineer',
          type: 'Full Stack, Full-Time',
          company: 'Indomaret Group',
          industry: 'Warehouse & Logistics.',
          location: 'Jakarta, Indonesia',
          date: '2020 - present',
          image: 'indomaret.jpg',
          description: 'Create and develop warehouse systems, websites and desktop applications, ranging from processing, management, automation, job scheduling, monitoring to reporting used in all distribution centers on a national scale throughout Indonesia.'
        },
        {
          job: 'Angular Web. Developer',
          type: 'Frond End, Part-Time',
          company: 'MacroAd',
          industry: 'Digital Advertising.',
          location: 'Banten, Indonesia',
          date: '2019 - 2020',
          image: 'macroad.jpg',
          description: 'Create a website that is used by users in general and also a special page for Admin to manage it.'
        },
        {
          job: 'Computer Lab. Assistant',
          type: 'Full Stack, Part-Time',
          company: 'Univ. Multimedia Nusantara',
          industry: 'Teach Programming Course.',
          location: 'Banten, Indonesia',
          date: '2017 - 2019',
          image: 'umn.jpg',
          description: 'Algorithms & Data Structures, Database Systems, Graphics & Animations for game development and Website Development.'
        }
      ],
      papers: [
        {
          title: 'Go-Ethereum for Electronic Voting System Using Clique as Proof-of-Authority',
          description: 'Telkomnika, Vol 19, No 5: October 2021. Pp 1565-1572.',
          url: 'https://dx.doi.org/10.12928/telkomnika.v19i5.20415',
          publisher: 'Telkomnika',
          date: '01 October 2021',
          images: [
            'https://avataaars.io/?avatarStyle=Circle&topType=LongHairFrida&accessoriesType=Kurt&hairColor=Red&facialHairType=BeardLight&facialHairColor=BrownDark&clotheType=GraphicShirt&clotheColor=Gray01&graphicType=Skull&eyeType=Wink&eyebrowType=RaisedExcitedNatural&mouthType=Disbelief&skinColor=Brown',
            'https://avataaars.io/?avatarStyle=Circle&topType=ShortHairFrizzle&accessoriesType=Prescription02&hairColor=Black&facialHairType=MoustacheMagnum&facialHairColor=BrownDark&clotheType=BlazerSweater&clotheColor=Black&eyeType=Default&eyebrowType=FlatNatural&mouthType=Default&skinColor=Tanned',
            'https://avataaars.io/?avatarStyle=Circle&topType=LongHairMiaWallace&accessoriesType=Sunglasses&hairColor=BlondeGolden&facialHairType=Blank&clotheType=BlazerSweater&eyeType=Surprised&eyebrowType=RaisedExcited&mouthType=Smile&skinColor=Pale'
          ]
        },
        {
          title: 'A Secured Online Voting System by Using Blockchain as the Medium',
          description: 'The Smart Cyber Ecosystem for Sustainable Development, Chapter 21.',
          url: 'https://doi.org/10.1002/9781119761655.ch21',
          publisher: 'Scrivener Publishing LLC',
          date: '12 September 2021',
          images: [
            'https://avataaars.io/?avatarStyle=Circle&topType=LongHairDreads&accessoriesType=Prescription01&hairColor=BrownDark&facialHairType=BeardMajestic&facialHairColor=Platinum&clotheType=GraphicShirt&clotheColor=Gray02&graphicType=Skull&eyeType=Default&eyebrowType=UpDown&mouthType=ScreamOpen&skinColor=Black',
            'https://avataaars.io/?avatarStyle=Circle&topType=ShortHairFrizzle&accessoriesType=Prescription02&hatColor=Gray02&hairColor=BrownDark&facialHairType=BeardMajestic&facialHairColor=Blonde&clotheType=Overall&clotheColor=Gray02&graphicType=Diamond&eyeType=Dizzy&eyebrowType=RaisedExcited&mouthType=Vomit&skinColor=Yellow',
            'https://avataaars.io/?avatarStyle=Circle&topType=LongHairFrida&accessoriesType=Sunglasses&hairColor=Brown&facialHairType=MoustacheMagnum&facialHairColor=Blonde&clotheType=ShirtVNeck&clotheColor=Gray02&eyeType=Happy&eyebrowType=RaisedExcitedNatural&mouthType=Serious&skinColor=Tanned',
            'https://avataaars.io/?avatarStyle=Circle&topType=Eyepatch&accessoriesType=Prescription02&hairColor=SilverGray&facialHairType=MoustacheMagnum&facialHairColor=BrownDark&clotheType=Hoodie&clotheColor=Blue03&eyeType=WinkWacky&eyebrowType=Default&mouthType=Tongue&skinColor=Tanned',
            'https://avataaars.io/?avatarStyle=Circle&topType=LongHairStraight&accessoriesType=Round&hairColor=Blue&facialHairType=Blank&facialHairColor=Brown&clotheType=ShirtScoopNeck&clotheColor=Gray01&eyeType=Cry&eyebrowType=Default&mouthType=Sad&skinColor=Pale'
          ]
        }
      ]
    }),
  }
</script>
