<template>
  <v-app>
    <v-main>
      <Home />
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
    Home: () => import(/* webpackPrefetch: true */ '@/views/Home.vue'),
    Footer: () => import(/* webpackPrefetch: true */ '@/components/ui/Footer'),
  },

  data: () => ({
    //
  }),
};
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Caveat&family=Open+Sans&display=swap');
  body {
    background-color: #604FCD!important;
  }

</style>
