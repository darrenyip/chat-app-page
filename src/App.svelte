<script>

</script>

<style>
  main {
    width: 100%;
    position: relative;
    overflow: hidden;
  }
  .left-cover {
    position: absolute;
    width: 51rem;
    height: 101.8rem;
    border-radius: 255px;
    background-image: linear-gradient(225deg, #e844ff 0%, #8739ff 100%);
    z-index: -1;
    top: -68rem;
    left: -39rem;
  }
  .right-cover {
    position: absolute;
    width: 51rem;
    height: 101.8rem;
    border-radius: 255px;
    background-image: linear-gradient(225deg, #e844ff 0%, #8739ff 100%);
    z-index: -1;
    top: 20rem;
    left: 12rem;
    opacity: 0.03;
  }
  .app-container {
    width: 228px;
    margin: 0 auto;
    margin-top: 64px;
    background: #ffffff;
    box-shadow: 0px 30px 60px -10px rgba(62, 39, 83, 0.251202);
    border-radius: 30px;
    padding: 11px 9.5px;
  }
  .app-inner-container {
    background: #f5f3f7;
    /* border: 1px solid rgba(62, 39, 83, 0.0509178); */
    border-radius: 20px;
  }
  .app-header {
    overflow: hidden;
    position: relative;
    display: flex;
    background: linear-gradient(225deg, #e844ff 0%, #8739ff 100%);
    box-shadow: 0px 0px 13px rgba(62, 39, 83, 0.251202);
    border-radius: 20px 20px 6px 6px;
  }
  .header-cutout {
    height: 50px;
    width: 129px;
    position: absolute;
    background: white;
    border-radius: 12px;
    right: 53px;
    top: -30px;
  }
  .header-info {
    width: 196px;
    padding: 0 16.5px 0 15.5px;
    display: flex;
    align-items: center;
    padding-top: 30px;
    padding-bottom: 12px;
  }
  .back-btn {
    margin-right: 8px;
  }
  .back-btn button {
    padding: 0;
    margin: 0;
  }
  .person-icon {
    width: 24px;
    height: 24px;
    border-radius: 50%;
    margin-right: 8px;
  }
  .person-icon img {
    width: 100%;
    border-radius: 50%;
  }
  .back-btn button {
    border: none;
    background: transparent;
  }
  .person-info {
    flex: 1 0;
  }
  .person-info .name {
    font-style: normal;
    font-weight: 500;
    font-size: 11px;
    line-height: 13px;
    color: #ffffff;
  }
  .person-info .status {
    font-style: normal;
    font-weight: normal;
    font-size: 8px;
    line-height: 9px;

    color: #d99eff;
  }
  .app-chat-box {
    padding: 11px 7.5px 10px 7.5px;
  }
  .user-text-imgs {
    display: flex;
    justify-content: flex-end;
  }

  .dog-image-container {
    width: 136px;
    height: 40px;
    display: flex;
    justify-content: space-around;
    margin-bottom: 14px;
  }
  .img-box {
    height: 40px;
    width: 40px;
    box-shadow: 0px 10px 5px -5px rgba(62, 39, 83, 0.045318);
  }
  .img-box img {
    width: 100%;
    border-radius: 10px;
    /* box-shadow: 0px 10px 5px -5px rgba(62, 39, 83, 0.045318); */
  }
  .incomming-text {
    background: #eee5f4;
    border-radius: 10px 10px 10px 4px;
    margin-bottom: 14px;
    max-width: 128px;
    padding: 6px 8px;
  }
  .incomming-text p {
    font-style: normal;
    font-weight: normal;
    font-size: 8px;
    line-height: 11px;
    /* or 137% */

    color: #9341c8;
  }
  .user-text-container {
    display: flex;
    justify-content: flex-end;
  }
  .user-text {
    background: #ffffff;
    box-shadow: 0px 10px 5px -5px rgba(62, 39, 83, 0.045318);
    border-radius: 10px 10px 4px 10px;
    max-width: 128px;
    padding: 6px 8px;
    margin-bottom: 14px;
  }
  .user-text p {
    font-style: normal;
    font-weight: normal;
    font-size: 8px;
    line-height: 11px;
    /* or 137% */

    color: #6e5d7e;
  }
  .price-option {
    background: linear-gradient(225deg, #e844ff 0%, #8739ff 100%);
    box-shadow: 0px 10px 5px -5px rgba(62, 39, 83, 0.045318);
    border-radius: 10px 10px 10px 4px;
    margin-bottom: 14px;
    width: 160px;
    padding: 10px 16px 10px 8px;
    display: flex;
    align-content: center;
  }
  .price-option .circle {
    margin-right: 8px;
  }
  .price-option .time {
    display: flex;
    align-items: center;
    flex: 1 0;
  }
  .price-option .time p {
    font-style: normal;
    font-weight: 400;
    font-size: 8px;
    line-height: 11px;
    color: #ffffff;
  }
  .price-option .price {
    display: flex;
    align-items: center;
  }
  .price-option .price p {
    font-style: normal;
    font-weight: bold;
    font-size: 12px;
    line-height: 11px;
    color: #ffffff;
  }
  form {
    display: flex;
    padding: 4.8px 7.5px;
    background: #ffffff;
    border-radius: 16.9544px;
    justify-content: space-between;
  }
  form input {
    border: none;
    text-indent: 16px;
  }
  form input::placeholder {
    font-style: normal;
    font-weight: normal;
    font-size: 9px;
    line-height: 11px;
    /* identical to box height */

    letter-spacing: -0.0703125px;

    color: #c5c9cc;
  }
  .send-btn {
    border: none;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #3e2753;
    width: 24.27px;
    height: 24.27px;
  }
  .ads {
    margin-top: 64px;
    padding: 0 32px 0 32px;
    margin-bottom: 64px;
  }
  .ads h1 {
    font-style: normal;
    font-weight: 500;
    font-size: 40px;
    line-height: 47px;
    text-align: center;
    color: #3e2753;
    margin-bottom: 24px;
  }
  .ads p {
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 28px;
    text-align: center;
    color: #a39da9;
  }

  @media (min-width: 1400px) {
    main {
      max-width: 1440px;
      margin: 0 auto;
    }
    .container {
      padding: 148px 260px 147px 363px;
      display: flex;
    }
    .container .app-container {
      margin-left: 125px;
    }
    .left-cover {
      width: 510px;
      height: 1018px;
      top: -25%;
      left: -6.5%;
    }
    .right-cover {
      width: 510px;
      height: 1018px;
      top: 11%;
      left: 75%;
    }
    .container {
      align-items: center;
    }
    .container .app-container {
      margin-left: 0;
    }
    .ads {
      width: 445px;
    }
    .ads h1 {
      text-align: left;
      font-style: normal;
      font-weight: 500;
      font-size: 40px;
      line-height: 47px;
      color: #3e2753;
    }
    .ads p {
      text-align: left;
      font-style: normal;
      font-weight: normal;
      font-size: 16px;
      line-height: 28px;
      /* or 175% */

      color: #a39da9;
    }
  }
</style>

<main>
  <div class="left-cover" />
  <div class="right-cover" />
  <div class="container">
    <!-- app -->
    <section class="app-container">
      <!-- app header -->
      <div class="app-inner-container">
        <div class="app-header">
          <div class="header-cutout" />
          <div class="header-info">
            <div class="back-btn">
              <button>
                <svg
                  width="4"
                  height="10"
                  viewBox="0 0 4 10"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg">
                  <path
                    d="M2.10557 0.552792C2.35256 0.0588133 2.95324 -0.141411
                    3.44721 0.105578C3.90591 0.334925 4.11131 0.869235 3.94056
                    1.3399L3.89443 1.44722L2.118 5.00001L3.89443 8.55279C4.12377
                    9.01149 3.96751 9.56218 3.54851 9.83626L3.44721
                    9.89443C2.98852 10.1238 2.43783 9.96752 2.16374
                    9.54852L2.10557 9.44722L0.105573 5.44722C-0.0150818 5.20591
                    -0.0323182 4.92798 0.0538637 4.67621L0.105573
                    4.55279L2.10557 0.552792Z"
                    fill="white" />
                </svg>
              </button>
            </div>
            <div class="person-icon">
              <img src="./images/avatar.jpg" alt="" />
            </div>
            <div class="person-info">
              <p class="name">Samuel Green</p>
              <p class="status">Available to Walk</p>
            </div>
            <div class="triple-dot">
              <svg
                width="2"
                height="8"
                viewBox="0 0 2 8"
                fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M2 1C2 1.55228 1.55228 2 1 2C0.447715 2 0 1.55228 0 1C0
                  0.447715 0.447715 0 1 0C1.55228 0 2 0.447715 2 1ZM2 4C2
                  4.55228 1.55228 5 1 5C0.447715 5 0 4.55228 0 4C0 3.44772
                  0.447715 3 1 3C1.55228 3 2 3.44772 2 4ZM1 8C1.55228 8 2
                  7.55228 2 7C2 6.44772 1.55228 6 1 6C0.447715 6 0 6.44772 0 7C0
                  7.55228 0.447715 8 1 8Z"
                  fill="white" />
              </svg>

            </div>
          </div>
        </div>
        <div class="app-chat-box">
          <div class="incomming-text">
            <p>That sounds great. I'd be happy to discuss more.</p>
          </div>
          <div class="incomming-text">
            <p>Could you send over some pictures of your dog, please?</p>
          </div>
          <div class="user-text-imgs">
            <div class="dog-image-container">
              <div class="img-box">
                <img src="./images/dog-image-1.jpg" alt="" />
              </div>
              <div class="img-box">
                <img src="./images/dog-image-2.jpg" alt="" />
              </div>
              <div class="img-box">
                <img src="./images/dog-image-3.jpg" alt="" />
              </div>
            </div>

          </div>
          <div class="user-text-container">
            <div class="user-text">
              <p>Here are a few pictures. She's a happy girl!</p>
            </div>
          </div>
          <div class="user-text-container">
            <div class="user-text">
              <p>Can you make it?</p>
            </div>
          </div>

          <div class="incomming-text">
            <p>
              She looks so happy! The time we discussed works. How long shall I
              take her out for?
            </p>
          </div>
          <div class="price-option">
            <div class="circle">
              <svg
                width="12"
                height="12"
                viewBox="0 0 12 12"
                fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <circle cx="6" cy="6" r="5.5" stroke="#E472FF" />
              </svg>
            </div>
            <div class="time">
              <p>30 minute walk</p>
            </div>
            <div class="price">
              <p>$29</p>
            </div>
          </div>
          <div class="price-option">
            <div class="circle">
              <svg
                width="12"
                height="12"
                viewBox="0 0 12 12"
                fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <circle cx="6" cy="6" r="5.5" stroke="#E472FF" />
              </svg>
            </div>
            <div class="time">
              <p>1 hour walk</p>
            </div>
            <div class="price">
              <p>$49</p>
            </div>
          </div>
          <form action="">
            <input type="text" placeholder="Type a message..." />
            <button class="send-btn">
              <svg
                width="7"
                height="10"
                viewBox="0 0 7 10"
                fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M1.06419 0.465024C1.50167 0.0284666 2.19006 -0.00511479
                  2.66614 0.36428L2.78047 0.465024L6.42125 4.09812C6.85873
                  4.53467 6.89238 5.22161 6.52221 5.69669L6.42125
                  5.81077L2.78047 9.44387C2.30653 9.9168 1.53813 9.9168 1.06419
                  9.44387C0.626713 9.00731 0.59306 8.32038 0.963236
                  7.8453L1.06419 7.73121L3.84588 4.95445L1.06419
                  2.17768C0.626713 1.74112 0.59306 1.05419 0.963236
                  0.579112L1.06419 0.465024Z"
                  fill="white" />
              </svg>

            </button>
          </form>
        </div>

      </div>

    </section>
    <!-- body text -->
    <section class="ads">
      <h1>Simple booking</h1>
      <p>
        Stay in touch with our dog walkers through the chat interface. This
        makes it easy to discuss arrangements and make bookings. Once the walk
        has been completed you can rate your walker and book again all through
        the chat.
      </p>
    </section>
  </div>

</main>
