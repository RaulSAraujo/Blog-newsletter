<template>
    <v-app-bar min-height="60" app flat>
      <img src="../assets/logo.png" alt="Logo" width="110" />

      <v-tabs centered v-model="$store.state.tab" class="ml-n9" color="grey darken-1">
        <v-tab v-for="link in links" :key="link">
          {{ link }}
        </v-tab>
      </v-tabs>
    </v-app-bar>
</template>

<script>
export default {
  name: "App",
  data(){
    return{
    links: ["QUEM SOU", "SOLUÇÕES", "ARTIGOS"],
    }
  },
};
</script>

<style scoped>

</style>