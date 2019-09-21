<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>GSWebDev</span><br>
        <span class="font-weight-light">VueJS Calculator</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      
    </v-app-bar>

    <v-content>
      <Calculator/>
       
    </v-content>
  </v-app>
</template>

<script>
import Calculator from './components/Calculator';

export default {
  name: 'App',
  components: {
    Calculator,
  },
  data: () => ({
    //
  }),
};
</script>
