<template>
  <v-app dark>
    <v-app-bar
      fixed
      app
      color="primary"
      dark
    >
      <v-spacer />
      <v-toolbar-title v-text="title" />
      <v-spacer />
    </v-app-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer
      absolute
      app
    >
      <span>&copy; Hanna Maman {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      title: 'LABORATOIRE D\'ANALYSE MEDICAL'
    }
  }
}
</script>
