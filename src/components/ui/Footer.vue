<template>
  <div>
    <div class="d-flex justify-center">
      <span class="title">Contáctanos</span> 
    </div>
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
  .title{
    position: absolute;
    margin-top: 200px;
    font-family: 'Caveat', cursive !important;
    font-size: 80px !important;
    font-weight: 700;
    color: #3F454A !important;
  }

  .send-button{
    width: 170px;
    height: 55px !important;
  }

</style>