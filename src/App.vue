<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <TabelaAvaliacao/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import TabelaAvaliacao from './components/TabelaAvaliacao';
export default {
  name: 'App',

  components: {
    HelloWorld,
    TabelaAvaliacao
  },

  data: () => ({
    //
  }),
};
</script>
