<template>
  <v-container fluid class="py-6 secondary--text">
    <h1 align="center" class="py-6 mt-3 font-weight-medium">
      DEVELOPER'S BLOGS
    </h1>
    <v-row justify="center">
      <v-col cols="11" lg="6" class="text-center my-6">
        <iframe
          class="note-embed my-5"
          src="https://note.com/embed/notes/na73cc8154c5c"
          style="
            border: 0;
            display: block;
            max-width: 99%;
            width: 494px;
            position: static;
            visibility: visible;
          "
          height="400"
        ></iframe>
        <script
          async
          src="https://note.com/scripts/embed.js"
          charset="utf-8"
        ></script>

        <iframe
          class="note-embed my-5"
          src="https://note.com/embed/notes/ncd698b7e7c1b"
          style="
            border: 0;
            display: block;
            max-width: 99%;
            width: 494px;
            position: static;
            visibility: visible;
          "
          height="400"
        ></iframe>
        <script
          async
          src="https://note.com/scripts/embed.js"
          charset="utf-8"
        ></script>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {}
</script>
<style scoped>
.contact-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
