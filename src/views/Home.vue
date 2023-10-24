<template>
  <div>
    <Hero />
    <v-row justify="end">
      <v-col cols="12" md="3"></v-col>
      <v-col cols="12" md="9">
        <Cards />
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components:{
    Hero: () => import(/* webpackPrefetch: true */ '@/components/hero/Hero.vue'),
    Cards: () => import(/* webpackPrefetch: true */ '@/components/cards/Cards.vue'),
  },

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

</style>