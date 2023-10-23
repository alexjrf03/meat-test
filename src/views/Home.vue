<template>
  <div>
    <Hero />
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components:{
    Hero: () => import(/* webpackPrefetch: true */ '@/components/hero/Hero.vue'),
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