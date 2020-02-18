<template>
  <div class="home">
    <!-- <ButtonAndIcons />
    <TextStaffVue />
    <BreakPointAndVisibility />
    <Themes /> -->
    <h1 class="subheading grey--text">HomePage</h1>
    <v-container  class="my-5">
      <v-layout row wrap >
        <v-flex xs12 md6 >
          <v-btn outlined block  color="primary">
            1
          </v-btn>
          
        </v-flex>
        <v-flex xs4 md2>
          <v-btn outlined block  color="primary">
            1
          </v-btn>
          
        </v-flex>
        <v-flex xs4 md2>
          <v-btn outlined block  color="primary">
            1
          </v-btn>
          
        </v-flex>
        <v-flex xs4 md2>
          <v-btn outlined block  color="primary">
            1
          </v-btn>
          
        </v-flex>
      </v-layout> 
      <v-layout row wrap justify-center class="my-5">
        <v-flex xs4 md3>
          <v-btn outlined block class="success">
            1
          </v-btn>
        </v-flex>
        <v-flex xs4 md3>
          <v-btn outlined block class="success">
            1
          </v-btn>
        </v-flex>
        
      </v-layout>
    </v-container>
  </div>
</template>

<script>
import TextStaffVue from '../components/01.TextStaff.vue'
import ButtonAndIcons from '../components/02.ButtonAndIcons'
import BreakPointAndVisibility from '../components/03.BreakPointsAndVisibility'
import Themes from '../components/05.Themes'
  

export default {
  name: 'Home',
  components: {
    // eslint-disable-next-line vue/no-unused-components
    TextStaffVue,
    // eslint-disable-next-line vue/no-unused-components
    ButtonAndIcons,
    // eslint-disable-next-line vue/no-unused-components
    BreakPointAndVisibility,
    // eslint-disable-next-line vue/no-unused-components
    Themes
  }
}
</script>
