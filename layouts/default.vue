<template>
  <v-app>
    <v-app-bar absolute color="white" elevate-on-scroll>
      <v-app-bar-title>{{title}}</v-app-bar-title>

    </v-app-bar>
      <nuxt />
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      title: 'Auto Club'
    }
  }
}
</script>

<style scoped>

</style>
