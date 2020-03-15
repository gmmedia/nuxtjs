<template>
  <v-app>
    <v-app-bar app color="white" min-height="64px">
      <v-toolbar-title>Title</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn text>Link One</v-btn>
        <v-btn text>Link Two</v-btn>
        <v-btn text>Link Three</v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-content>
      <v-row justify="center">
        <v-col cols="xl-6">
          <nuxt />
        </v-col>
      </v-row>
    </v-content>
    <v-footer
      class="font-weight-medium"
      color="grey lighten-3"
    >
      <v-col
        class="text-center"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-footer>
  </v-app>
</template>

<style>
</style>
