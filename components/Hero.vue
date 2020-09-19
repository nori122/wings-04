<template>
  <!-- <v-parallax src="img/hero_bg_mobile.jpg">
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12">
          <h1 class="display-1 font-weight-thin mb-4">Vuetify.js</h1>
          <h4 class="subheading">Build your application today!</h4>
        </v-col>
      </v-row>
    </v-parallax> -->
  <!-- <v-img src="img/hero_bg_mobile.jpg" height="90vh">
    <v-row align="center" justify="center">
      <v-col class="text-center" cols="12">
        <h1 class="display-1 font-weight-thin mb-4">Vuetify.js</h1>
        <h4 class="subheading">Build your application today!</h4>
      </v-col>
    </v-row>
  </v-img> -->
  <v-app>
    <v-content class="bg" fluid fill-height>
      <v-row justify="center">
        <v-col class="text-center white--text" cols="8">
          <h1 class="display-1 font-weight-bold mb-4">個人のための</h1>
          <h1 class="display-1 font-weight-bold mb-4">コンテンツ</h1>
          <h1 class="display-1 font-weight-bold mb-4">翻訳サービス</h1>
        </v-col>
        <v-col class="text-center blue-grey--text text--darken-4" cols="12">
          <h4 class="display-4">Wings</h4>
        </v-col>
      </v-row>
    </v-content>
    <!-- <v-parallax
      dark
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12">
          <h1 class="display-1 font-weight-thin mb-4">Vuetify.js</h1>
          <h4 class="subheading">Build your application today!</h4>
        </v-col>
      </v-row>
    </v-parallax> -->
  </v-app>
</template>
<script>
export default {
  //   name: 'Hero',
}
</script>
<style scoped>
div {
  overflow: hidden;
}
.bg {
  /* width: 100%;
  height: 100%;
  position: absolute; */
  background-size: cover;
  background-image: url('/img/hero_bg_mobile.jpg');
}
</style>
