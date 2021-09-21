<template>
  <v-app>
    <TopBar/>
    <router-view/>
  </v-app>
</template>

<script>
import TopBar from './components/TopBar.vue'
export default {
  name: 'App',
  components:{
    TopBar
  },
  data: () => ({
    
  }),
  
};
</script>
