<template>
  <div>
    <h2 class="mt-6">Contáctanos</h2>
    <v-container>

        <v-row justify="center">
          <v-col cols="12" md="4">
            <v-text-field
              class="inputs"
                outlined
            ></v-text-field>
          </v-col>
  
          <v-col cols="12" md="4">
            <v-text-field
              outlined
            ></v-text-field>
          </v-col>
        </v-row>

      <v-row justify="center">
        <v-col cols="12" md="4">
          <v-text-field
            class="inputs"
            outlined
            color="primary"
          ></v-text-field>
        </v-col>

        <v-col cols="12" md="4">
          <v-text-field
            class="inputs"
            outlined
          ></v-text-field>
        </v-col>
      </v-row>
      <center>
        <v-btn
          class="send-button"
          rounded
          elevation="0"
          color="primary"
        >
          Enviar
        </v-btn>
      </center>
    </v-container>
  </div>
</template>

<script>
export default {
  name: 'FooterView',

  data() {
    return {
      
    };
  },

  mounted() {
    
  },

  methods: {
    
  },
};
</script>

<style lang="scss" scoped>

  .send-button{
    width: 170px;
    height: 55px !important;
  }

</style>