<template>
  <v-app>
    <v-app-bar class="pa-6" absolute color="white" elevate-on-scroll>
      <v-app-bar-title>{{title}}</v-app-bar-title>
       <v-tabs align-with-title>
          <v-tab>Tab 1</v-tab>
          <v-tab>Tab 2</v-tab>
          <v-tab>Tab 3</v-tab>
        </v-tabs>
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
