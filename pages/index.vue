<template>
  <div>
    <heading size="3xl">
      Solo Adventure
    </heading>
    <div class="flex flex-col">
      <div class="flex flex-row">
        <sa-button type="primary">
          Start Adventure
        </sa-button>
      </div>
    </div>
  </div>
</template>
<script>
import Heading from '~/components/utility/text/Heading.vue'
import SaButton from '~/components/utility/button/Button.vue'

export default {
  components: {
    Heading,
    SaButton
  }
}
</script>
