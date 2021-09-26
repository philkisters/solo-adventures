<template>
  <div class="">
    <slot />
  </div>
</template>
<script>
export default {
  props: {
    size: {
      typeof: String,
      default: 'md'
    }
  }
}
</script>
