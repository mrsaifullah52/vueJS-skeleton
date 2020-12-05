<template>
  <footer class="page-footer blue-grey darken-3">
    <div class="container">
      <div class="row">
        <div class="col l6 s12">
          <h5 class="white-text">Student Name</h5>
          <p class="grey-text text-lighten-4">Details about Student...</p>
        </div>
        <div class="col l4 offset-l2 s12">
          <h5 class="white-text">Important</h5>
          <ul>
            <li>
              Primary Email:
              <a class="grey-text text-lighten-3" href="#"
                >student@example.com</a
              >
            </li>
            <li>
              Secondary Email:
              <a class="grey-text text-lighten-3" href="#"
                >student@example.com</a
              >
            </li>
            <li>
              Phone:
              <a class="grey-text text-lighten-3" href="#">123-456-7890</a>
            </li>
            <li>Borrower Status: In Good Standing</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer-copyright blue-grey darken-4">
      <div class="container center">© 2020 Copyright</div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.bottom p {
  margin: 0px !important;
  padding: 10px 0px;
}
</style>