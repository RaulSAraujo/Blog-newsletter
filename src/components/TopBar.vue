<template>
    <v-app-bar min-height="60" app flat>
      <img src="../assets/Logo-Versão_2.0.png" alt="Logo" width="100" />

      <v-tabs centered v-model="$store.state.tab" class="ml-n9" color="red lighten-3">
        <v-tabs-slider color="red lighten-3"></v-tabs-slider>
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
    links: ["QUEM SOU", "FORMAS DE TRABALHO","BLOG"],
    }
  },
};
</script>

<style scoped>

</style>