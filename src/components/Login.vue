<template>
  <div class="login">



    <div class="field">
      <label class="label is-medium">Account</label>
      <div class="control has-icons-left">
        <input class="input is-medium" type="text">
        <span class="icon is-small is-left">
          <i class="fa fa-user"></i>
        </span>
      </div>
    </div>
    <div class="field">
      <label class="label is-medium">Password</label>

      <div class="control has-icons-left">
        <input class="input is-medium" type="password">
        <span class="icon is-small is-left">
          <i class="fa fa-lock"></i>
        </span>
      </div>
    </div>
    <div class="field">
      <p class="control">
        <button class="button is-success">
          Login
        </button>
      </p>
    </div>

  </div>
</template>
<script>
  export default {

  }

</script>
<style>
  .login {
    background: url('../assets/bg_login.png') no-repeat center center;
    background-size: cover;
    height: 890px;
    width: 100%
  }

</style>
