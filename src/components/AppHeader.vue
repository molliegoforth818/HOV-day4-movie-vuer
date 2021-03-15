<template>
  <v-app-bar app color="red darken-1" dark>
    <h1>Movie Vuer</h1>
    <form @submit.prevent="handleSubmit" style="background: white">
      <input type="text" v-model="query" />
    </form>
  </v-app-bar>
</template>

<script>
export default {
  data() {
    return {
      query: "",
    };
  },
  methods: {
    handleSubmit() {
      console.log("Search for:", this.query);
    },
  },
};
</script>