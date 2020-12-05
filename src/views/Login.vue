<template>
  <div class="form-container">
    <div class="form">
      <div class="form_avatar">
        <img src="../assets/userImg.png" alt="user_avatar" />
      </div>
      <form class="col s12">
        <div class="row">
          <div class="input-field col s12">
            <input id="username" type="text" class="validate" />
            <label for="username">Username</label>
          </div>
        </div>
        <div class="row">
          <div class="input-field col s12">
            <input id="password" type="password" class="validate" />
            <label for="password">Password</label>
          </div>
        </div>
        <div class="forgot">
          <p>Forgot Your Password? <a href="#">Click Here</a></p>
        </div>

        <div class="btn">
          <router-link to="/home">LOGIN</router-link>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>
<style scoped>
.my_Nav {
  display: none !important;
}
.form-container {
  height: 100vh;
  width: 100%;
  background-color: #139ac7e7;
  padding-top: 100px;
}
.form_avatar {
  position: absolute;
  top: -42px;
  left: 43%;
}
.form_avatar img {
  width: 100px;
  height: 80px;
  border-radius: 50%;
}
.form {
  position: relative;
  background-color: #fff;
  width: 50% !important;
  margin: 0px auto;
  padding: 50px;
}
.btn {
  background-color: #139ac7e7 !important;
  margin: 0px auto !important;
  width: 80px;
  height: 40px;
}
.btn a {
  color: #fff !important;
}
</style>