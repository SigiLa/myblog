<template>

  <div class="header">
    <div class="logo">
      <a href="/">
        <h2>ShareKits</h2>
      </a>
    </div>
    <ul v-if="loginStatus" class="navication">
      <li>
        <a style="color:#fff" href="/login">登录</a>
      </li>
      <span>/</span>
      <li>
        <a style="color:#fff" href="/register">注册</a>
      </li>
    </ul>
  </div>

</template>

<script>
  export default {
    data() {
      return {
        loginStatus: true
      }
    }
  }

</script>
<style>
  div.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding-left: 10rem;
    padding-right: 10rem;
  }

  .logo h2 {
    font-family: 'TrashHand';
    color: #fff;
    font-size: 2em;
    letter-spacing: 0.1rem;
  }

  ul.navication {
    display: flex;
    font-size: 1.5em;
    font-weight: 500;
    color: #fff;
  }

</style>
