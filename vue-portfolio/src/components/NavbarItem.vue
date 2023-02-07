<template>
  <v-app-bar app color="#111" dark flat class="px-8 contains">
    <div class="logo">
      <span>{</span>Vico<span>}</span>
    </div>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('projects')">Project</v-btn>
    <v-btn text @click="scroll('about')">About</v-btn>
    <v-btn text @click="scroll('contact')">Contacts</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
@import "../../dist/css/app.css";
</style>