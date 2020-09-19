<template>
  <div>
    <Hero />
    <Vision />
    <Service />
    <Contact />
  </div>
  <!-- グリッドシステムのチェック -->
  <!-- <v-container fluid>
    <v-row align="center" justify="center">
      <v-col class="grey lighten-3" cols="8">
        <p>1</p>
      </v-col>
      <v-spacer />
      <v-col class="grey lighten-4" cols="4">
        <p>2</p>
      </v-col>
    </v-row>
  </v-container> -->
</template>
<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'
import Hero from '~/components/Hero.vue'
import Vision from '~/components/Vision.vue'
import Service from '~/components/Service.vue'
import Contact from '~/components/Contact.vue'

export default {
  components: {
    Hero,
    Vision,
    Service,
    Contact,
  },
}
</script>
