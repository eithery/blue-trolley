<template>
  <v-app dark>
    <v-app-bar fixed app>
      <v-toolbar-title v-text="title" />
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer fixed app />
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: 'Blue Trolley'
    }
  }
}
</script>
