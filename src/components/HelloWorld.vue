<template>
   <div>
     <v-toolbar flat class="elevation-5">
        <div>
          <v-toolbar-title>Avaliações</v-toolbar-title>
        </div>
        <v-spacer></v-spacer>
     
        <div class="button-toolbar">
          <v-btn
            color="black"
            dark
            class="ma-2"
            @click="showFilter({ show: true })"
            small
            ><v-icon>mdi-filter</v-icon></v-btn
          >
          <v-btn color="black" dark class="ma-2" @click="reload" small
            ><v-icon>mdi-refresh</v-icon></v-btn
          >
        </div>
      </v-toolbar>
   </div>
     
</template>

<script>
export default {
  methods: {
    reload(){
      parent.location="javascript:location.reload()"
    },
   
  },
  
}
</script>


