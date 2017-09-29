<template>

  <div class="header">
    <a href="/" style="background-color:#fff">
      <h1>
        <img src="../assets/imgs/alien.png">
      </h1>
    </a>
    <ul class="log">
      <li>Welcome to Amazing UFO,</li>
      <li>Join US</li>
      <li>Sign in</li>
    </ul>
    <ul class="log2">
      <select class="lang changelang">
        <option value="0">Change Language</option>
        <option value="en">English</option>
        <option value="tc">繁體中文</option>
        <option value="sc">简体中文</option>
      </select>
    </ul>
    <div class="wrapnav">
      <ul class='nav'>


      </ul>

    </div>
  </div>

</template>

<script>
  export default {

  }

</script>
<style>
  div.header {
    width: 1200px;
    height: 160px;
    z-index: 5;
    background: #fff;
    position: relative;
    margin: 20px auto;
  }

  .header h1 {
    display: flex;
    justify-content: center;
    width: 218px;
    height: 140px;
    float: left;
  }

  .header h1 > img {
    height: 140px;
    width: auto;
    text-align: center;

  }

  ul.log {
    position: absolute;
    top: 5px;
    left: 220px;
    font-family: Arial, Helvetica, sans-serif;
  }

  .log li {
    font-size: 11px;
    display: inline;
  }

  ul.log2 {
    position: absolute;
    top: 5px;
    right: 70px;
    font-family: Arial, Helvetica, sans-serif;
  }

  select.lang {
    border: none;
    padding: 0;
    margin: 0;
    font-size: 11px;
    font-family: Arial, Helvetica, sans-serif;
  }

  .wrapnav {
    background: #fff;
  }

  ul.nav {
    float: right;
    height: 60px;
    border-top: 1px solid;
    border-bottom: 1px solid;
    margin: 30px;
    width: 900px;
    position: relative;
    left: -50px;
  }



</style>
