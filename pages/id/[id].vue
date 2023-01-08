<template>
  <div>id {{ route.params.id }} page</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    const route = useRoute();

    return {
      route,
    };
  },
});
</script>
