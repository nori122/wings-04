<template>
  <v-app>
    <div>
      <v-container fluid fill-height class="secondary--text">
        <v-row align="center" justify="center">
          <v-col class="pa-lg-12" cols="10" lg="6" order-lg="3">
            <v-img src="img/heroimg.png"></v-img>
          </v-col>
          <v-col class="text-center" cols="10" lg="4" order-lg="1">
            <h1 class="text-h4 text-lg-h3 py-5">
              あなたのプロダクトを、海外のユーザーに届けよう
            </h1>
            <h2 class="text-body-2 text-lg-h6 py-5" order-lg="2">
              Wingsは、DeepLの機械翻訳と海外のネイティブスピーカーによる翻訳サービスです。ブログ記事の翻訳により、あなたのプロダクトを世界のユーザーに届けます。
            </h2>
            <v-btn
              class="my-5 py-5"
              rounded
              color="accent"
              href="https://forms.gle/7pQ6PnjvHtTj3Bb6A"
              dark
              >お問い合わせ
            </v-btn>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </v-app>
</template>
<script>
export default {}
</script>
<style scoped>
div {
  overflow: hidden;
}
h1,
h2 {
  font-family: 'M PLUS Rounded 1c', sans-serif;
}
.wings {
  font-family: 'Kalam', serif;
  font-size: 100px;
}
</style>
