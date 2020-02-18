<template>
  <div class="home">
    <!-- <ButtonAndIcons /> -->
    <!-- <TextStaffVue /> -->
    <!-- <BreakPointAndVisibility /> -->
    <ToolBars />
  </div>
</template>

<script>
import TextStaffVue from '../components/01.TextStaff.vue'
import ButtonAndIcons from '../components/02.ButtonAndIcons'
import BreakPointAndVisibility from '../components/03.BreakPointsAndVisibility'
import ToolBars from '../components/04.ToolBars'
  

export default {
  name: 'Home',
  components: {
    // eslint-disable-next-line vue/no-unused-components
    TextStaffVue,
    // eslint-disable-next-line vue/no-unused-components
    ButtonAndIcons,
    // eslint-disable-next-line vue/no-unused-components
    BreakPointAndVisibility,
    ToolBars
  }
}
</script>
