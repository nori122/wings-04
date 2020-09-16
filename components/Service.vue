<template>
  <v-container fluid fill-height>
    <v-row align="center" justify="center" class="my-6"
      ><v-col>
        <v-row class="mx-2">
          <v-col> <h1>サービスの流れ</h1></v-col></v-row
        >
        <v-row>
          <v-col>
            <v-card>
              <v-card-title>1. 翻訳のお申し込み</v-card-title>
              <v-img align="center" class="pa-3">
                <img class="service-image" src="../assets/img/contact.svg"
              /></v-img>
              <v-card-text
                >コンタクトフォームからお申し込みください。</v-card-text
              >
            </v-card>
            <v-row align="center" justify="center" class="py-8"
              ><v-icon size="30">mdi-arrow-down-thick</v-icon></v-row
            >
            <v-card>
              <v-card-title>2. 機械翻訳を実施</v-card-title>
              <v-img align="center" class="pa-3">
                <img class="service-image" src="../assets/img/mt.svg"
              /></v-img>
              <v-card-text
                >コンタクトフォームからお申し込みください。</v-card-text
              >
            </v-card>
          </v-col>
        </v-row>
      </v-col></v-row
    >
  </v-container>
</template>

<script>
export default {}
</script>
<style scoped>
div {
  background-color: white;
}
.service-image {
  width: 60%;
}
</style>
