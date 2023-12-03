

<template>
    <div class="sign-in-container">
      <div class="sign-in-sign-in">
        <img src="C:\Users\rodyn\OneDrive\Desktop\Algoriza-Fe039-project\rectangle27.png" alt="Rectangle1190" class="sign-in-rectangle1" />
        <span class="sign-in-text"><span>Email address</span></span>
        <span class="sign-in-text02"><span>Password</span></span>
        <div class="sign-in-frame14">
          <div class="sign-in-bxsplanealt1">
            <div class="sign-in-group">
              <img
                src="/path/to/vector1114-cnzp.svg"
                alt="Vector1114"
                class="sign-in-vector"
              />
            </div>
          </div>
          <span class="sign-in-text04"><span>my Dream Place</span></span>
        </div>
        <div class="sign-in-emailaddress">
          <span class="sign-in-text06"><span>Email address</span></span>
        </div>
        <div class="sign-in-password">
          <span class="sign-in-text08"><span>Enter password</span></span>
          <div class="sign-in-eye1">
            <div class="sign-in-group1">
              <img
                src="/path/to/vectori111-7k7u.svg"
                alt="VectorI111"
                class="sign-in-vector1"
              />
              <img
                src="/path/to/vectori111-y5ts.svg"
                alt="VectorI111"
                class="sign-in-vector2"
              />
            </div>
          </div>
        </div>
        <div class="sign-in-group22 sign-in">
          <span class="sign-in-text10"><span>Sign in</span></span>
        </div>
        <span class="sign-in-text12">
          <span class="sign-in-text13">
            Don’t have an account?
            <span v-html="rawkj4d"></span>
          </span>
          <span>Register</span>
        </span>
        <span class="sign-in-text15"><span>Sign in</span></span>
      </div>
    </div>
  </template>
  
  <script>
    export default {
      name: 'SignIn',
      props: {},
      data() {
        return {
          rawkj4d: ' ',
          isDarkMode: false, // Add this variable for dark mode
        };
      },
      methods: {
        toggleDarkMode() {
          this.isDarkMode = !this.isDarkMode;
        },
      },
    };
    </script>
  
  <style scoped>
  .sign-in-container {
    width: 100%;
    display: flex;
    overflow: auto;
    min-height: 100vh;
    align-items: center;
    flex-direction: column;
  }
  .sign-in-sign-in {
    width: 100%;
    height: 970px;
    display: flex;
    overflow: hidden;
    position: relative;
    align-items: flex-start;
    flex-shrink: 0;
    background-color: rgba(255, 255, 255, 1);
  }
  .sign-in-rectangle1 {
    top: 0px;
    left: 0px;
    width: 1440px;
    height: 68px;
    position: absolute;
  }
  .sign-in-text {
    top: 232px;
    left: 520px;
    color: rgba(24, 24, 24, 1);
    height: auto;
    position: absolute;
    font-size: 14px;
    font-weight: 500;
    line-height: 139.9999976158142%;
    text-decoration: none;
  }
  
  .sign-in-group22.sign-in {
    /* Updated class name */
    top: 421px;
    left: 520px;
    width: 400px;
    height: 43px;
    display: flex;
    position: absolute;
    align-items: flex-start;
    flex-shrink: 1;
    background-color: rgba(47, 128, 237, 1);
  }
  /* ... (other styles) ... */
  </style>
  