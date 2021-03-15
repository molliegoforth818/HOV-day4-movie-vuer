<template>
  <v-app>
    <v-app-bar app color="teal-darken-4" dark>
    <v-main>
      <v-container>
        <search-results />
      </v-container>
    </v-main>
     </v-app>
</template>

<script>
import SearchResults from "./components/SearchResults";

export default {
  components: {
    SearchResults,
  },
}
</script>
