<template>
  <div class="home">
    <NavBar />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import NavBar from '~/components/NavBar.vue'

export default Vue.extend({
  components: {
    NavBar
  }
})
</script>

<style lang="scss" scopes>
.home {
  width: 100%;
  height: 100%;
}
</style>
