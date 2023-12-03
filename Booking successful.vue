<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Booking successful</title>
</head>
<body>
    <template>
        <div class="bookingsuccessful-container">
          <div class="bookingsuccessful-bookingsuccessful">
            <span class="bookingsuccessful-text"><span>Booking Successful</span></span>
            <span class="bookingsuccessful-text2">
              <span>
                Congratulations your reservation has been made. You will be notified 2
                days prior the date.
              </span>
            </span>
            <div class="bookingsuccessful-frame13">
              <span class="bookingsuccessful-text4"><span>View Trip</span></span>
            </div>
            <img src alt="Rectangle211217" class="bookingsuccessful-rectangle21" />
            <img src alt="image111217" class="bookingsuccessful-image11" />
          </div>
        </div>
      </template>
      
      <script>
      export default {
        name: 'Bookingsuccessful',
        props: {},
      }
      </script>
      
      <style scoped>
      .bookingsuccessful-container {
        width: 100%;
        display: flex;
        overflow: auto;
        min-height: 100vh;
        align-items: center;
        flex-direction: column;
      }
      .bookingsuccessful-bookingsuccessful {
        width: 100%;
        height: 500px;
        display: flex;
        position: relative;
        align-items: flex-start;
        flex-shrink: 0;
        border-radius: 10px;
        background-color: rgba(255, 255, 255, 1);
      }
      .bookingsuccessful-text {
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
      .bookingsuccessful-text2 {
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
      .bookingsuccessful-frame13 {
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
      .bookingsuccessful-text4 {
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
      .bookingsuccessful-rectangle21 {
        top: 50px;
        left: 80px;
        width: 240px;
        height: 200px;
        position: absolute;
        border-radius: 10px;
      }
      .bookingsuccessful-image11 {
        top: 70px;
        left: 120px;
        width: 160px;
        height: 160px;
        position: absolute;
      }
      </style>
      
</body>
</html>