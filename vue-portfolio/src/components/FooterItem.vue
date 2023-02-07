<template>
  <v-footer dark padless>
    <v-card
      flat
      tile
      class="block white--text py-5 px-5 text-center"
      width="100%"
    >
      <v-row>
        <v-col cols="12" sm="4">
          <v-card-text class="white--text pt-2">
            <div class="logo"><span>{</span>Vico<span>}</span></div>
          </v-card-text>
        </v-col>
        <v-col cols="12" sm="4">
          <v-card-text class="pt-2">
            <ul class="social-links">
              <li>
                <a href="#">
                  <v-icon color="#227909">fa-brands fa-facebook</v-icon>
                </a>
              </li>
              <li>
                <a href="#">
                  <v-icon color="#227909">fa-brands fa-linkedin</v-icon>
                </a>
              </li>
              <li>
                <a href="#">
                  <v-icon color="#227909">fa-brands fa-github</v-icon>
                </a>
              </li>
              <li>
                <a href="#">
                  <v-icon color="#227909">fa-brands fa-twitter</v-icon>
                </a>
              </li>
            </ul>
          </v-card-text>
        </v-col>
        <v-col cols="12" sm="4">
          <v-card-text class="pt-2">
            <v-btn class="mx-1 white--text" icon>
              <v-icon color="#227909">fas fa-heart</v-icon>
            </v-btn>
            <a href="github.com" class="created white--text">Created by Vico</a>
          </v-card-text>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
</script>

<style>
@import "../../dist/css/app.css";
</style>