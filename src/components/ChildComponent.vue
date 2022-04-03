<template>
  <div>
    <slot v-bind:example="example">
    </slot>
  </div>
</template>

<script>

export default {
  name: 'ChildComponent',
  data() {
    return {
      example: 'just some data...'
    }
  }
}
</script>
