<template>
  <child-component>
    <template v-slot:default="slotProps">
      Now we can use the data from the child component here: {{ slotProps.example }}
    </template>
  </child-component>
</template>

<script>
import ChildComponent from "./components/ChildComponent.vue";

export default {
  name: 'App',
  components: {
    ChildComponent
  }
}
</script>
