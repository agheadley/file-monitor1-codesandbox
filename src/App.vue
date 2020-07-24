<template>
  <div id="app">
    <v-app>
      <v-app-bar app>Monitor v1</v-app-bar>
      <v-main>
        <v-container fluid>
          <Monitor/>
        </v-container>
      </v-main>
      <v-footer app>AGH</v-footer>
    </v-app>
  </div>
</template>

<script>
import Monitor from "./components/Monitor";

export default {
  name: "App",
  components: {
    Monitor
  }
};
</script>