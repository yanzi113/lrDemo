<script setup></script>
<template>
  <div class="box">
    <div class="container">
      <div class="top-header">
        <h2>Login</h2>
      </div>
      <div class="input-field">
        <input type="text" class="input" placeholder="Username" required />
      </div>
      <div class="input-field">
        <input type="password" class="input" placeholder="Password" required />
      </div>
      <div class="input-field">
        <input type="submit" class="submit" value="Login" />
      </div>
      <div class="bottom">
        <div class="left">
          <input type="checkbox" id="check" />
          <label for="check"></label>
        </div>
        <div class="right">
          <a href="#">注册</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.box {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
}
.container{
    width: 400px;
    padding: 20px;
    background: #ffffff00;
    box-shadow: inset 0 0 10px #eceaea;
}
</style>
