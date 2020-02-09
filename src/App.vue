<template>
  <div id="app" class="p-10 text-xl">
    <BaseIcon name="home" class="text-blue-500" /> Home
    <BaseIcon name="user" class="text-blue-500" /> Profile
  </div>
</template>

<script>
import BaseIcon from './components/BaseIcon.vue'

export default {
  name: 'App',
  components: {
    BaseIcon
  }
}
</script>
