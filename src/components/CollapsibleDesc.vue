<template>
  <a href="#">{{ desc }}</a>
</template>

<script>
export default {
  name: "CollapsibleDesc",
  props: {
    desc: String,
  },
};
</script>