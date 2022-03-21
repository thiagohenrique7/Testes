<template>
    <v-data-table
      :headers="headers"
      :items="desserts"
      :items-per-page="10"
      class="elevation-1"
    >
    </v-data-table>
</template>


<script>
// import VSwitch from "v-switch-case";
// import Vue from "vue";
// Vue.use(VSwitch);

export default {
  data() {
    return {
      headers: [
        {
          text: "Data",
          align: "start",
          value: "data",
        },
        { text: "Cliente", value: "cliente" },
        { text: "Atendente", value: "atendente" },
        { text: "Nota", value: "nota" },
        { text: "Estrela", value: "estrela"}
      ],
      desserts: [
        {
          data: "15/12/2000",
          cliente: "thiago.nog",
          atendente: "Luis",
          nota: 5,
        },
        {
          data: "15/10/2003",
          cliente: "julia.faria",
          atendente: "Gabriel",
          nota: 4,
        },
        {
          data: "21/10/1999",
          cliente: "joao.lucas",
          atendente: "Maria",
          nota: 3.5,
        },
        {
          data: "02/08/1998",
          cliente: "pedro.lucas",
          atendente: "Gabriel",
          nota: 4.5,
        },
        {
          data: "01/09/1995",
          cliente: "pedro.carlos",
          atendente: "Luis",
          nota: 2,
        },
        {
          data: "15/11/2000",
          cliente: "carlos.nog",
          atendente: "Maria",
          nota: 5,
        },
        {
          data: "11/11/2000",
          cliente: "lucas.nog",
          atendente: "Joao",
          nota: 3,
        },
        {
          data: "10/11/2000",
          cliente: "gus.lut",
          atendente: "Pedro",
          nota: 5,
        },
        {
          data: "20/10/1999",
          cliente: "pedro.mout",
          atendente: "Luis",
          nota: 4.5,
        },
        {
          data: "10/12/2000",
          cliente: "mig.vid",
          atendente: "Luis",
          nota: 4,
        },
      ],
    };
  },
};
</script>