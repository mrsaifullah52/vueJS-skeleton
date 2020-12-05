<template>
  <tr>
    <td>
      {{ name }}
      <br />
      <a href="#">Remove Item</a>
    </td>

    <td>
      <input type="number" name="count" id="count" v-bind:value="count" />
    </td>
    <td>${{ price }}</td>
  </tr>
</template>

<script>
export default {
  name: "CartRow",
  props: {
    name: String,
    count: Number,
    price: Number,
  },
};
</script>

<style scoped>
input {
  width: 50px !important;
  height: 30px !important;
  padding-left: 5px;
}
a {
  color: red;
  font-size: 10px;
}
</style>