<template>
  <el-row class="container">
    <Item :type="'signup'" />
  </el-row>
</template>

<script>
import Item from '../components/LoginItem'
export default {
  data() {
    return {}
  },
  components: {
    Item,
  },
  methods: {},
}
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
