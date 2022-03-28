<template>
  <v-app>
    <HeaderApp/>

    <v-main class="text-right">
      <router-view/>
    </v-main>

    <FooterApp/>
  </v-app>
</template>

<script>

import FooterApp from './components/Footer.vue';
import HeaderApp from './components/Header.vue';

export default {
  name: 'App',

  data: () => ({
    //
  }),
  components:{
    FooterApp,
    HeaderApp
  }
};
</script>
