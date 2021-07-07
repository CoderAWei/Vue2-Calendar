<template>
  <div class="home">
    <!-- <VueQr
      :bgSrc='bgSrc'
      :text='text'
      :size='500'
      :dotScale='dotScale'
      :autoColor='false'
      colorDark='#ffb3a7'
    /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <calendar
      width="100%"
      :can-select="false"
      select-mode="move"
      :start-of-week="3"
      @dateSelected="handleDateSelected"
    />

    <el-calendar
      :first-day-of-week="7"
    />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
// import VueQr from 'vue-qr'
import calendar from '../components/Calendar'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    // VueQr
    calendar
  },
  data() {
    return {
    }
  },
  created() {

  },
  methods: {
    handleDateSelected(val) {
      console.log(val)
    }
  }
}
</script>
