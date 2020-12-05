<template>
  <div class="container">
    <h3>Your Shoping Cart</h3>
    <p>You have selected</p>
    <div class="row">
      <div class="cart_table col m8">
        <table class="responsive-table">
          <thead class="deep-orange darken-1">
            <tr>
              <th>Product Name</th>
              <th>Item Count</th>
              <th>Item Price</th>
            </tr>
          </thead>

          <tbody>
            <CartRow
              name="Canon Digital Rebel SL3"
              v-bind:count="1"
              v-bind:price="57.81"
            />
            <CartRow
              name="Canon Digital Rebel SL2"
              v-bind:count="1"
              v-bind:price="77.12"
            />
            <CartRow
              name="Canon Digital Rebel SL5"
              v-bind:count="1"
              v-bind:price="99.53"
            />
          </tbody>
        </table>
      </div>

      <div class="bill_table col m4">
        <h5 class="deep-orange darken-1">
          Total Bill <span class="right">$284.63</span>
        </h5>
        <div class="items_count">
          <h6>Total Items: <span class="right">3</span></h6>
          <h6>Bill: <span class="right">$247.83</span></h6>
          <h6>Tax: <span class="right">$47.34</span></h6>
          <div class="check_out">
            <span class="btn deep-orange">Proceed to Checkout</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import CartRow from "../components/CartRow";
export default {
  name: "Cart",
  components: {
    CartRow,
  },
};
</script>

<style scoped>
thead {
  color: #fff !important;
}
.bill_table h5 {
  color: #fff;
  margin: 0px;
  padding: 12px 5px;
}
.bill_table h6 {
  padding: 30px 15px;
  border-bottom: 1px solid #eee;
}
.btn {
  width: 100% !important;
}
</style>

