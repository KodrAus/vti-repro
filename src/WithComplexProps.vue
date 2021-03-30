<template>
  <div>
    {{ data.value }}
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { PropType } from 'vue'

import { Complex } from './complex'

export default Vue.extend({
  props: {
      data: {
          type: Object as PropType<Complex>,
          required: true
      }
  }
})
</script>
