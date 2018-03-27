<template>
  <div id="login">
      <p class="title">{{msg}}</p>
      <div class="login-content">
        <p class="login-user">
          <b></b>
          <span class="line"></span>
          <input type="text" name="" placeholder="请输入手机号">
        </p>
        <p class="security-code">
          <b></b>
          <span class="line"></span>
          <input type="text" name="" placeholder="请输入验证码">
          <a class="getnumber">获取</a>
        </p>
        <van-button class="login-btn" @click="goHome()" bottom-action>登  录</van-button>
      </div>
  </div>
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      msg: '天津移动渠道集中化系统'
    }
  },
  methods: {
      goHome:function(){
          this.$router.push({name:'home',param:{}});
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #login {
      background: url("./../assets/img/background_login.jpg") no-repeat;
      background-size: cover;
      height: 28rem;
  }
  #login .title{
      margin: auto;
      color: #636D6A;
      font-size: 0.8rem;
      position: absolute;
      left: 0;
      right: 0;
      top: 7.1rem;
      text-align: center;
      width: 9rem;
      height: 2rem;
      line-height: 2rem;
  }
  #login .login-content {
      width: 90%;
      height: 30%;
      margin: auto;
      padding-top: 64%;
  }
  .login-user, .login-psw, .security-code, .from-account {
      width: 100%;
      height: 1.5rem;
      position: relative;
      box-sizing: border-box;
      padding-left: 1.5rem;
      border-bottom: 1px solid #ddd;
  }

  .login-user, .login-psw, .from-account {
      margin-bottom: 1.3rem;
  }

  .security-code {
      margin-bottom: 2rem;
  }

  .login-user > input, .login-psw > input, .security-code > input {
      width: 100%;
      height: 90%;
      border: none;
      outline: none;
      font-size: 0.6rem;
  }
  .login-user > b, .login-psw > b, .security-code > b {
      display: inline-block;
      width: 0.6rem;
      height: 0.6rem;
      position: absolute;
      top: 0;
      bottom: 0;
      left: 0;
      margin: auto;
  }  
  .login-user > b {
      background: url(./../assets/img/user_icon.png) no-repeat;
      background-size: 100% 100%;
  }
  .security-code > b {
      background: url(./../assets/img/security_code.png) no-repeat;
      background-size: 100% 100%;
  }
  .line {
      position: absolute;
      height: 0.5rem;
      top: 0;
      bottom: 0;
      left: 1rem;
      width: 1px;
      background: #ddd;
      margin: auto;
  }
  .login-psw > a, .security-code > a {
      width: 2.13rem;
      height: 1.11rem;
      border: 1px solid #00ce6d;
      color: #00ce6d;
      text-align: center;
      line-height: 1.11rem;
      font-size: 0.6rem;
      border-radius: 5px;
      position: absolute;
      right: 0;
      top: 0;
      bottom: 0;
      margin: auto;
  }
  .security-code > a.getSecurityCode {
      display: none;
      width: 5rem;
      color: #c5c5c5!important;
      border: 1px solid #ebebeb!important;
      background-color: #f6f6f6!important;
  }
  .login-btn {
      width: 90%;
      height: 1.88rem;
      line-height: 1.88rem;
      background: #00ce6d;
      border-radius: 5px;
      text-align: center;
      color: #fff;
      font-size: 0.768rem;
      margin: auto;
  }
</style>
