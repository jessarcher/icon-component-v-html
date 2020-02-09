<template>
  <div
    v-html="require(`../assets/icons/icon-${name}.svg`)"
    class="inline-block fill-current"
    style="height: 1em; width: 1em; vertical-align: -0.125em;"
  />
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      required: true,
    }
  }
}
</script>
