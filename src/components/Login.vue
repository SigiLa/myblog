<template>
  <div class="login">
    <div class="auth-form">
      <form accept-charset="UTF-8" action="" method="post">
        <div class="auth-form-header">
          <h1>Sign in to ShareKits</h1>
        </div>
        <div class="auth-form-body">
          <div class="field">
            <label class="label">帐号</label>
            <div class="control has-icons-left">
              <input class="input" type="text">
              <span class="icon is-left">
                <i class="fa fa-user"></i>
              </span>
            </div>
          </div>
          <div class="field">
            <label class="label">
              密码
              <a href="/password_reset" class="label-link">忘记密码?</a>
            </label>
            <div class="control has-icons-left">
              <input class="input" type="password">
              <span class="icon is-left">
                <i class="fa fa-lock"></i>
              </span>
            </div>
          </div>
          <div class="field">
            <p class="control">
              <button id="btn-login" class="button is-success">
                登录
              </button>
            </p>
            <p class="tip-register">没有账号?
              <a href="/register">注册帐号</a>
            </p>

          </div>
        </div>
      </form>
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
    width: 100%;
    padding-top: 130px;
  }

  .auth-form {
    width: 340px;
    margin: 0 auto;
    padding-left: 16px !important;
    padding-right: 16px !important;
  }

  .auth-form-header {
    text-align: center;
    color: #333;
    border: 0;
    background-color: transparent;
    margin-bottom: 20px;
    padding: 0;
  }

  .auth-form-header h1 {
    font-family: 'TrashHand';
    font-size: 30px;
    font-weight: 300;
    letter-spacing: -0.5px;
  }


  .auth-form-body {
    background-color: #fff;
    border: 1px solid #d8dee8;
    padding: 25px 20px;
    border-radius: 5px;
    border-top: 1px solid #d8dee8;
  }

  #btn-login {
    width: 100%;
  }

  .label-link {
    font-size: 12px;
    font-weight: normal;
    float: right;
    color: #0366d6;
    border: 1px solid transparent;
  }

  .label-link:hover {
    text-decoration: underline;
    color: #0366d6;
  }
  .tip-register{
    font-size: 12px;
    margin-top: 10px;
  }
  .tip-register a{
    color: #0366d6;
    float: right;
  }
  .tip-register a:hover{
    text-decoration: underline;
  }

</style>
