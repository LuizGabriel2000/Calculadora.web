<template>
  <v-app>
    <v-main>
      <Calculadora/>
    </v-main>
  </v-app>
</template>

<script>
import Calculadora from './components/Calculadora.vue';

export default {
  name: 'App',

  components: {
    Calculadora
},

  data: () => ({
    //
  }),
};
</script>
