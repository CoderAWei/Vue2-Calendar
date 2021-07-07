<template>
  <div class="container">
    <!-- <el-button type="primary">保存</el-button> -->
    <el-calendar
      v-model="value"
      :first-day-of-week="7"
    />
  </div>
</template>

<script>

export default {
  components: {
  },
  props: {

  },
  data() {
    return {
      value: new Date()
    }
  },
  computed: {

  },
  watch: {

  },
  created() {
  },
  mounted() {
  },
  methods: {

  }
}
</script>

<style scoped lang="scss">

</style>
