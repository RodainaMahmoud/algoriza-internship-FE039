<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Sign Up page</title>
    <script src="https://unpkg.com/vue@3.0.2"></script>
</head>
<body>
    <template>
        <div class="register-container">
          <div class="register-register">
            <img src alt="Rectangle11231" class="register-rectangle1" />
            <div class="register-group23">
              <span class="register-text"><span>Submit</span></span>
            </div>
            <span class="register-text02"><span>Email address</span></span>
            <span class="register-text04"><span>Password</span></span>
            <span class="register-text06"><span>Confirm password</span></span>
            <div class="register-frame14">
              <div class="register-bxsplanealt1">
                <div class="register-group">
                  <img
                    src="/vector1234-k3pm.svg"
                    alt="Vector1234"
                    class="register-vector"
                  />
                </div>
              </div>
              <span class="register-text08"><span>my Dream Place</span></span>
            </div>
            <div class="register-emailaddress">
              <span class="register-text10"><span>Email address</span></span>
            </div>
            <div class="register-password">
              <span class="register-text12"><span>Enter password</span></span>
              <div class="register-eye1">
                <div class="register-group1">
                  <img
                    src="/vectori123-i0t.svg"
                    alt="VectorI123"
                    class="register-vector1"
                  />
                  <img
                    src="/vectori123-on4.svg"
                    alt="VectorI123"
                    class="register-vector2"
                  />
                </div>
              </div>
            </div>
            <div class="register-password1">
              <span class="register-text14"><span>Enter password</span></span>
              <div class="register-eye11">
                <div class="register-group2">
                  <img
                    src="/vectori123-urpo.svg"
                    alt="VectorI123"
                    class="register-vector3"
                  />
                  <img
                    src="/vectori123-37qm.svg"
                    alt="VectorI123"
                    class="register-vector4"
                  />
                </div>
              </div>
            </div>
            <span class="register-text16"><span>Register</span></span>
            <span class="register-text18">
              <span class="register-text19">
                Already have an account?
                <span v-html="raw5nuy"></span>
              </span>
              <span>Sign in</span>
            </span>
          </div>
        </div>
      </template>
      
      <script>
      export default {
        name: 'Register',
        props: {},
        data() {
          return {
            raw5nuy: ' ',
          }
        },
      }
      </script>
      
      <style scoped>
      .register-container {
        width: 100%;
        display: flex;
        overflow: auto;
        min-height: 100vh;
        align-items: center;
        flex-direction: column;
      }
      .register-register {
        width: 100%;
        height: 970px;
        display: flex;
        overflow: hidden;
        position: relative;
        align-items: flex-start;
        flex-shrink: 0;
        background-color: rgba(255, 255, 255, 1);
      }
      .register-rectangle1 {
        top: 0px;
        left: 0px;
        width: 1440px;
        height: 68px;
        position: absolute;
      }
      .register-group23 {
        top: 509px;
        left: 520px;
        width: 400px;
        height: 43px;
        display: flex;
        position: absolute;
        align-items: flex-start;
        flex-shrink: 1;
        background-color: rgba(47, 128, 237, 1);
      }
      .register-text {
        top: 11px;
        left: 174px;
        color: rgba(255, 255, 255, 1);
        height: auto;
        position: absolute;
        font-size: 15px;
        font-style: Medium;
        text-align: left;
        font-family: Inter;
        font-weight: 500;
        line-height: 20px;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-text02 {
        top: 232px;
        left: 520px;
        color: rgba(24, 24, 24, 1);
        height: auto;
        position: absolute;
        font-size: 14px;
        font-style: Medium;
        text-align: left;
        font-family: SF Pro Display;
        font-weight: 500;
        line-height: 139.9999976158142%;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-text04 {
        top: 320px;
        left: 520px;
        color: rgba(24, 24, 24, 1);
        height: auto;
        position: absolute;
        font-size: 14px;
        font-style: Medium;
        text-align: left;
        font-family: SF Pro Display;
        font-weight: 500;
        line-height: 139.9999976158142%;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-text06 {
        top: 408px;
        left: 520px;
        color: rgba(24, 24, 24, 1);
        height: auto;
        position: absolute;
        font-size: 14px;
        font-style: Medium;
        text-align: left;
        font-family: Inter;
        font-weight: 500;
        line-height: 139.9999976158142%;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-frame14 {
        gap: 4px;
        top: 22px;
        left: 100px;
        width: 159px;
        display: flex;
        position: absolute;
        align-items: center;
      }
      .register-bxsplanealt1 {
        width: 24px;
        height: 24px;
        display: flex;
        overflow: hidden;
        position: relative;
        align-items: flex-start;
        flex-shrink: 0;
      }
      .register-group {
        top: 3.974423408508301px;
        left: 2px;
        width: 18.288578033447266px;
        height: 18.333112716674805px;
        display: flex;
        position: absolute;
        align-items: flex-start;
        flex-shrink: 1;
      }
      .register-vector {
        top: 7.926104217403918e-12px;
        left: 0px;
        width: 18px;
        height: 18px;
        position: absolute;
      }
      .register-text08 {
        color: rgba(27, 30, 44, 1);
        height: auto;
        font-size: 18px;
        font-style: Medium;
        text-align: left;
        font-family: SF Pro Display;
        font-weight: 500;
        line-height: normal;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-emailaddress {
        gap: 10px;
        top: 256px;
        left: 520px;
        width: 400px;
        display: flex;
        padding: 11px 12px 12px;
        position: absolute;
        align-items: center;
        flex-shrink: 0;
        border-radius: 4px;
        background-color: var(--dl-color-default-gray6);
      }
      .register-text10 {
        color: var(--dl-color-default-gray6);
        height: auto;
        font-size: 15px;
        font-style: Regular;
        text-align: left;
        font-family: SF Pro Display;
        font-weight: 400;
        line-height: 139.9999976158142%;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-password {
        gap: 10px;
        top: 344px;
        left: 520px;
        width: 400px;
        display: flex;
        padding: 11px 12px 12px;
        position: absolute;
        align-items: center;
        flex-shrink: 0;
        border-radius: 4px;
        background-color: var(--dl-color-default-gray6);
      }
      .register-text12 {
        color: var(--dl-color-default-gray6);
        height: auto;
        flex-grow: 1;
        font-size: 15px;
        font-style: Regular;
        text-align: left;
        font-family: SF Pro Display;
        font-weight: 400;
        line-height: 139.9999976158142%;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-eye1 {
        width: 20px;
        height: 20px;
        display: flex;
        overflow: hidden;
        position: relative;
        align-items: flex-start;
        flex-shrink: 0;
      }
      .register-group1 {
        top: 3.0999999046325684px;
        left: 1.8458335399627686px;
        width: 16.308334350585938px;
        height: 13.791667938232422px;
        display: flex;
        position: absolute;
        align-items: flex-start;
        flex-shrink: 1;
      }
      .register-vector1 {
        top: 3.9166665077209473px;
        left: 5.170832633972168px;
        width: 6px;
        height: 6px;
        position: absolute;
      }
      .register-vector2 {
        top: 0px;
        left: 0px;
        width: 16px;
        height: 14px;
        position: absolute;
      }
      .register-password1 {
        gap: 10px;
        top: 432px;
        left: 520px;
        width: 400px;
        display: flex;
        padding: 11px 12px 12px;
        position: absolute;
        align-items: center;
        flex-shrink: 0;
        border-radius: 4px;
        background-color: var(--dl-color-default-gray6);
      }
      .register-text14 {
        color: var(--dl-color-default-gray6);
        height: auto;
        flex-grow: 1;
        font-size: 15px;
        font-style: Regular;
        text-align: left;
        font-family: SF Pro Display;
        font-weight: 400;
        line-height: 139.9999976158142%;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-eye11 {
        width: 20px;
        height: 20px;
        display: flex;
        overflow: hidden;
        position: relative;
        align-items: flex-start;
        flex-shrink: 0;
      }
      .register-group2 {
        top: 3.0999999046325684px;
        left: 1.8458335399627686px;
        width: 16.308334350585938px;
        height: 13.791667938232422px;
        display: flex;
        position: absolute;
        align-items: flex-start;
        flex-shrink: 1;
      }
      .register-vector3 {
        top: 3.9166665077209473px;
        left: 5.170832633972168px;
        width: 6px;
        height: 6px;
        position: absolute;
      }
      .register-vector4 {
        top: 0px;
        left: 0px;
        width: 16px;
        height: 14px;
        position: absolute;
      }
      .register-text16 {
        top: 160px;
        left: 519px;
        color: rgba(24, 24, 24, 1);
        width: 401px;
        height: auto;
        position: absolute;
        font-size: 28px;
        font-style: Semibold;
        text-align: center;
        font-family: SF Pro Display;
        font-weight: 600;
        line-height: normal;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-text18 {
        top: 572px;
        left: 520px;
        color: rgba(79, 79, 79, 1);
        width: 400px;
        height: auto;
        position: absolute;
        font-size: 16px;
        font-style: Regular;
        text-align: center;
        font-family: SF Pro Display;
        font-weight: 400;
        line-height: normal;
        font-stretch: normal;
        text-decoration: none;
      }
      .register-text19 {
        color: var(--dl-color-default-gray2);
      }
      </style>
</body>      
</html>