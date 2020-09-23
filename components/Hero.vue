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
    <div class="hero-wrapper">
      <v-content class="bg" fluid fill-height>
        <v-row justify="center">
          <v-col class="text-center white--text mt-12" cols="8">
            <h3 class="sub-message font-weight-bold mt-12 mb-2">
              個人のための
            </h3>
            <h3 class="sub-message font-weight-bold mb-2">コンテンツ</h3>
            <h3 class="sub-message font-weight-bold mb-12">翻訳サービス</h3>
          </v-col>
          <v-col class="mt-12 text-center" cols="12">
            <h2 class="mt-12 wings blue-grey--text text--darken-4">Wings</h2>
          </v-col>
        </v-row>
      </v-content>
    </div>
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
export default {}
</script>
<style scoped>
div {
  overflow: hidden;
}
.bg {
  width: 100%;
  height: 100%;
  position: absolute;
  background-size: cover;
  background-image: url('/img/hero_bg_mobile.jpg');
}
.sub-message {
  font-family: 'Noto Sans JP', sans-serif;
  font-size: 35px;
}
.wings {
  font-family: 'Kalam', serif;
  font-size: 100px;
}
</style>
