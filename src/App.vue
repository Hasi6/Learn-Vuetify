<template>
  <v-app>
    <v-content>
      <ToolBar />
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
// eslint-disable-next-line no-unused-vars
import ToolBar from './components/04.ToolBars'
export default {
  name: 'App',

  components: {
    ToolBar
  },

  data: () => ({
    //
  }),
};
</script>
