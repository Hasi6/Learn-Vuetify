<template>
  <div class="home">
    <!-- <ButtonAndIcons />
    <TextStaffVue />
    <BreakPointAndVisibility />
    <Themes /> -->
    <h1 class="subheading grey--text">HomePage</h1>
    <v-container  class="my-5" >
      <v-card flat class="pa-3">
        <v-layout row wrap v-for="(project, index) in projects" :key="index">
          <v-flex xs12 md6>
            <div class="caption grey--text">Project Title</div>
            <div >{{project.title}}</div>
          </v-flex>
          <v-flex xs6 sm4 md2>
              <div class="catipn grey--text">Person</div>
              <dir>{{project.person}}</dir>
          </v-flex>
          <v-flex xs6 sm4 md2>
              <div class="catipn grey--text">Due By</div>
              <dir>{{project.due}}</dir>
          </v-flex>
          <v-flex xs6 sm4 md2>
              <div class="catipn grey--text">Status</div>
              <dir>{{project.status}}</dir>
          </v-flex>
        </v-layout>
      </v-card>
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
  data: ()=> ({
    projects: [
      {
        title: "Test1",
        person: "Hasi",
        due: "Test1",
        status: "Test1"
      },
      {
        title: "Test2",
        person: "Hasi",
        due: "Test2",
        status: "Test2"
      },
      {
        title: "Test3",
        person: "Hasi",
        due: "Test3",
        status: "Test3"
      },
      {
        title: "Test4",
        person: "Hasi",
        due: "Test4",
        status: "Test4"
      },
    ]
  }),
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
