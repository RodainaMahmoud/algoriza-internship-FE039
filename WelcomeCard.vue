<template>
    <div class="welcomecard-container">
      <div class="welcomecard-welcomecard">
        <span class="welcomecard-text"><span>Welcome to My Dream Place</span></span>
        <span class="welcomecard-text2">
          <span>
            You can now enjoy your travel experience with easy access to resources
            and more
          </span>
        </span>
        <div class="welcomecard-frame13">
          <span class="welcomecard-text4"><span>Get Started</span></span>
        </div>
        <img src alt="Rectangle211205" class="welcomecard-rectangle21" />
        <img src="/frame1205-gmua.svg" alt="Frame1205" class="welcomecard-frame" />
        <img src="/frame1210-xno8.svg" alt="Frame1210" class="welcomecard-frame1" />
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Welcomecard',
    props: {},
  }
  </script>
  
  <style scoped>
  .welcomecard-container {
    width: 100%;
    display: flex;
    overflow: auto;
    min-height: 100vh;
    align-items: center;
    flex-direction: column;
  }
  .welcomecard-welcomecard {
    width: 100%;
    height: 500px;
    display: flex;
    position: relative;
    align-items: flex-start;
    flex-shrink: 0;
    border-radius: 10px;
    background-color: rgba(255, 255, 255, 1);
  }
  .welcomecard-text {
    top: 295px;
    left: 24px;
    color: rgba(24, 24, 24, 1);
    width: 352px;
    height: auto;
    position: absolute;
    font-size: 20px;
    font-style: Semibold;
    text-align: center;
    font-family: SF Pro Display;
    font-weight: 600;
    line-height: normal;
    font-stretch: normal;
    text-decoration: none;
  }
  .welcomecard-text2 {
    top: 339px;
    left: 24px;
    color: var(--dl-color-default-gray2);
    width: 352px;
    height: auto;
    position: absolute;
    font-size: 16px;
    font-style: Regular;
    text-align: center;
    font-family: SF Pro Display;
    font-weight: 400;
    line-height: 139.9999976158142%;
    font-stretch: normal;
    text-decoration: none;
  }
  .welcomecard-frame13 {
    gap: 10px;
    top: 428px;
    left: 24px;
    width: 352px;
    display: flex;
    padding: 12px 18px;
    position: absolute;
    align-items: center;
    flex-shrink: 0;
    border-radius: 6px;
    justify-content: center;
    background-color: var(--dl-color-default-blue1);
  }
  .welcomecard-text4 {
    color: rgba(255, 255, 255, 1);
    height: auto;
    font-size: 15px;
    font-style: Medium;
    text-align: left;
    font-family: SF Pro Display;
    font-weight: 500;
    line-height: 20px;
    font-stretch: normal;
    text-decoration: none;
  }
  .welcomecard-rectangle21 {
    top: 50px;
    left: 80px;
    width: 240px;
    height: 200px;
    position: absolute;
    border-radius: 100px;
  }
  .welcomecard-frame {
    top: 58px;
    left: 180px;
    width: 112px;
    height: 192px;
    position: absolute;
  }
  .welcomecard-frame1 {
    top: 63px;
    left: 127px;
    width: 81px;
    height: 187px;
    position: absolute;
  }
  </style>
  