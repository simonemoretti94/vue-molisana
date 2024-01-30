<script >

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'app',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  data() {
    return {

    }
  }
}


</script>

<template>
  <AppHeader></AppHeader>

  <AppMain></AppMain>

  <AppFooter></AppFooter>
</template>



<style scoped></style>
