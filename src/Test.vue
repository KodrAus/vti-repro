<template>
  <div>
    <with-complex-props :data="complex" />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

import WithComplexProps from './WithComplexProps.vue'

export default Vue.extend({
  components: {
    WithComplexProps
  },
  data () {
    return {
      complex: {
        value: 'hello'
      }
    }
  }
})
</script>
