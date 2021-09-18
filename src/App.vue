<template>
  <v-app>
    <v-app-bar fixed dense elevate-on-scroll>
      <v-container class="pa-0 fill-height">
        <v-spacer></v-spacer>
        <v-btn icon href="mailto:bias.astho@gmail.com">
          <v-icon>mdi-at</v-icon>
        </v-btn>
        <v-btn icon href="https://linkedin.com/in/Bifeldy">
          <v-icon>mdi-linkedin</v-icon>
        </v-btn>
        <v-btn icon href="https://facebook.com/Bifeldy">
          <v-icon>mdi-facebook</v-icon>
        </v-btn>
        <v-btn icon href="https://instagram.com/Bifeldy">
          <v-icon>mdi-instagram</v-icon>
        </v-btn>
        <v-btn icon href="https://twitter.com/Bifeldy">
          <v-icon>mdi-twitter</v-icon>
        </v-btn>
        <v-btn icon href="https://github.com/Bifeldy">
          <v-icon>mdi-github</v-icon>
        </v-btn>
        <v-btn icon @click="toggleDarkMode">
          <v-icon>mdi-theme-light-dark</v-icon>
        </v-btn>
      </v-container>
    </v-app-bar>
    <v-main>
      <Home/>
    </v-main>
  </v-app>
</template>

<script>
import Home from './components/Home';

export default {
  name: 'App',
  components: {
    Home
  },
  data: () => ({
    darkMode: true
  }),
  mounted: function () {
    this.setDarkMode();
  },
  methods: {
    setDarkMode: function () {
      this.$vuetify.theme.dark = this.darkMode;
    },
    toggleDarkMode: function () {
      this.darkMode = !this.darkMode;
      this.setDarkMode();
    }
  }
};
</script>
