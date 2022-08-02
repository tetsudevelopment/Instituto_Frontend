<template>
  <v-app>

    <v-main>
      <!-- <HelloWorld/> -->
      <personal-area-inst/>

    </v-main>
  </v-app>
</template>

<script>
import PersonalAreaInst from './components/PersonalAreaInst.vue';
// import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    // HelloWorld,
    PersonalAreaInst
  },

  data: () => ({
    //
  }),
};
</script>
