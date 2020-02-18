<template>
  <div class="home">
    <ButtonAndIcons />
    <!-- <TextStaffVue /> -->
  </div>
</template>

<script>
import TextStaffVue from '../components/01.TextStaff.vue'
import ButtonAndIcons from '../components/02.ButtonAndIcons'

  

export default {
  name: 'Home',
  components: {
    // eslint-disable-next-line vue/no-unused-components
    TextStaffVue,
    ButtonAndIcons
  }
}
</script>
