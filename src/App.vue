<template>
  <v-app>
    <v-content >
      <ToolBar />
      <div class="mx-4 mb-4">
      <router-view></router-view>
      </div>
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
