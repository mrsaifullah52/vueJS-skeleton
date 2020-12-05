<template>
  <li>
    <div class="collapsible-header">{{ title }}</div>
    <div class="collapsible-body">
      <CollapsibleDesc v-bind:desc="description" />
    </div>
  </li>
</template>

<script>
import CollapsibleDesc from "./CollapsibleDesc";

export default {
  name: "Collapsible",
  components: {
    CollapsibleDesc,
  },
  props: {
    title: String,
    description: String,
  },
};
</script>

<style scoped>
.collapsible-header {
  font-weight: bold;
}
</style>