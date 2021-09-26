<template>
  <div :class="'text-' + size" class="text-gray-700">
    <slot />
  </div>
</template>
<script>
export default {
  props: {
    size: {
      type: String,
      default: 'base'
    }
  }
}
</script>
