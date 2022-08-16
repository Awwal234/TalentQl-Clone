<template>
  <center>
    <div class="text-container">
      <div class="intro_text">
        Build formidable teams with vetted, world-class tech talent.
      </div>
      <!---->
      <div class="intro-text2">
        We help companies build top-tier teams by hiring, developing and
        managing tech talent remotely.
      </div>
      <!---->
      <button class="talent-btn">
        Find your next talent <span><i class="las la-arrow-right"></i></span>
      </button>
    </div>

    <!---->
    <div class="im-space">
    <img src="/mobile_header-3ea6e9f6ace99d118b5f8c9ed0e26160.svg" alt="" />
    </div>

    <!---->
    <!--clients that trust us-->
    <div class="client-space">
        <div class="first-client-text">Clients that trust us</div>
        <div class="second-client-text">
            Since we launched operations in January 2021, we have helped 50+ companies across the world hire the
            technical talent they need.
        </div>
    </div>
    <!---->
    <div class="slide-sponsors"></div>
  </center>
</template>

<style scoped>
.text-container {
  justify-content: center;
  margin-top: 200px;
  position: relative;
  z-index: 30;
}
.intro_text {
  width: 60%;
  font-size: 50px;
  font-family: "Poppins", sans-serif;
  font-weight: bold;
  line-height: 61px;
}
.intro-text2 {
  width: 40%;
  font-size: 17px;
  font-family: "Poppins", sans-serif;
  margin-top: 30px;
  font-weight: 600;
  color: #374151;
}
.talent-btn {
  margin-top: 50px;
  padding: 20px;
  color: #fff;
  background: #000;
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  font-weight: bold;
  border-radius: 40px;
  cursor: pointer;
}
.talent-btn:hover {
  color: #9ca3af;
}
.im-space {
    display: none;
}
.client-space {
    margin-top: 100px;
    color: #111827;
}
.first-client-text {
    font-family: "Poppins", sans-serif;
    font-size: 30px;
    font-weight: 700;
}
.second-client-text {
    font-family: "Poppins", sans-serif;
    width: 70%;
    font-size: 18px;
    margin-top: 25px;
    font-weight: bold;
}
.slide-sponsors {
    width: 86%;
    border: 2px solid #d1d5db;
    border-radius: 11px;
    height: 40px;
    margin-top: 40px;
    padding: 30px;
}

@media only screen and (max-width:1024px) {
  .intro_text {
    width: 70%;
    font-size: 30px;
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    line-height: 35px;
  }
  .intro-text2 {
    width: 60%;
    font-size: 13px;
    font-family: "Poppins", sans-serif;
    margin-top: 15px;
    font-weight: 300;
    color: #374151;
  }
  .talent-btn {
    margin-top: 20px;
    padding: 15px;
    color: #fff;
    background: #000;
    font-family: "Poppins", sans-serif;
    font-size: 13px;
    font-weight: bold;
    border-radius: 40px;
  }
}

@media only screen and (max-width:767px) {
  .text-container {
    justify-content: center;
    margin-top: 100px;
  }
  .intro_text {
    width: 95%;
    font-size: 22px;
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    line-height: 35px;
  }
  .intro-text2 {
    width: 90%;
    font-size: 13px;
    font-family: "Poppins", sans-serif;
    margin-top: 15px;
    font-weight: 300;
    color: #374151;
  }
  .talent-btn {
    margin-top: 20px;
    padding: 15px;
    color: #fff;
    background: #000;
    font-family: "Poppins", sans-serif;
    font-size: 13px;
    font-weight: bold;
    border-radius: 40px;
  }
  .im-space {
    display: block;
    margin-top: 50px;
  }

  .first-client-text {
    font-family: "Poppins", sans-serif;
    font-size: 20px;
    font-weight: 700;
  }
  .second-client-text {
    font-family: "Poppins", sans-serif;
    width: 90%;
    font-size: 12px;
    margin-top: 25px;
    font-weight: bold;
  }
  .slide-sponsors {
    width: 90%;
    border: 2px solid #d1d5db;
    border-radius: 11px;
    height: 80px;
    margin-top: 40px;
    padding: 2%;
  }
}
</style>
