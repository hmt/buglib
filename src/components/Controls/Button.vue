<template>
  <button>
    <slot>default</slot>
  </button>
</template>

<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'TempUiButton',
})

</script>
