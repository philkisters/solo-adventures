<template>
  <button class="text-lg p-4" @click="$emit('click')">
    <slot />
  </button>
</template>
<script>
export default {
  props: {
    type: {
      type: String,
      default: 'default'
    }
  },
  data () {
    return {
      primaryClasses: {
        'text-white': true,
        'bg-yellow-600': true
      },
      defaultClasses: {
        'text-black': true,
        'bg-gray-100': true
      }
    }
  },
  computed: {
    style () {
      switch (this.type) {
        case 'primary':
          return this.primaryClasses
        default:
          return this.defaultClasses
      }
    }
  }
}
</script>
