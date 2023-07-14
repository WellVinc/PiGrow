<template>
 <v-layout class="rounded rounded-md">
    <v-app-bar title="PiGrowProject">
      
      <v-btn icon="PiGrowLogo.ico">
        
      </v-btn>
    
    </v-app-bar>

    <v-main class="d-flex align-center justify-center" style="min-height: 300px;">
      
      <v-img
        :width="width"
        :aspect-ratio="16/9"
        src= 'logo'>
      </v-img>
    </v-main>
  </v-layout>
</template>

<script>
import PiGrow from './assets/PiGrowLogo.png'
export default{
  data() {
    logo : PiGrow;
  }
}
/*import Test from './components/data.vue'

export default {
  name: 'App',
  components: {
    Test
  }
}
*/
</script>

<style>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
  background-color: #edecdc;
}

#app {
  height: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>