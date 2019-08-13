<template>
  <div class="flex">
    <nuxt-link active-class="active" :to="{ path: route }" class="py-5 px-10 hover:text-blue-600 text-gray-700">
      {{ text }}
    </nuxt-link>
  </div>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      required: true
    },
    route: {
      type: String,
      required: true
    }
  }
}
</script>

<style>
  .active {
    @apply text-blue-600
  }
</style>
