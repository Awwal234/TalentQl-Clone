<template>
<div>
  <div class="header-container">
    <header>
      <div>
        <img src="/talentql-logo.svg" alt="" />
      </div>
      <!---->
      <div>
        <ul class="header-list">
          <li>
            For Employers <span><i class="las la-angle-down"></i></span>
          </li>
          <li>
            For Developers <span><i class="las la-angle-down"></i></span>
          </li>
          <li>
            About Us <span><i class="las la-angle-down"></i></span>
          </li>
        </ul>
      </div>
      <!---->
      <div class="btn">
        <button class="header-btn1">Join TalentQL</button>
        <button class="header-btn2">Hire talent</button>
      </div>
      <!---->
      <div class="menu">
        <i class="las la-bars"></i>
      </div>
    </header>
  </div>
  <HeroSection />
  <SerchEnd />
</div>
</template>

<script>
import HeroSection from "@/components/HeroSection.vue";
import SerchEnd from "@/components/SerchEnd.vue";
export default {
  components: {
    HeroSection,
    SerchEnd,
  },
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300&display=swap');
.header-container {
  width: 100%;
  background: #fff;
  margin-right: -8px;
  margin-left: -8px;
  margin-top: -8px;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-right: 8px;
  padding-left: 8px;
  z-index: 9999;
}
header {
  width: 90%;
  padding: 20px;
  background: #fff;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header-list {
  list-style-type: none;
  display: flex;
  font-size: 15px;
  font-family: "Poppins", sans-serif;
  font-weight: 900;
}
.header-list > li {
  margin-right: 70px;
  cursor: pointer;
}
.btn {
  display: flex;
}
.btn > button {
  margin-right: 20px;
}
.header-btn1 {
  width: fit-content;
  height: fit-content;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 25px;
  padding-right: 25px;
  border-radius: 40px;
  background: #f3f4f6;
  border: 0px;
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  font-weight: bold;
  cursor: pointer;
}
.header-btn1:hover {
  background: #d1d5db;
  box-shadow: 1px 1px 8px 1px #9ca3af;
}
.header-btn2 {
  width: fit-content;
  height: fit-content;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 25px;
  padding-right: 25px;
  border-radius: 40px;
  background: #000;
  border: 0px;
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  font-weight: bold;
  color: #fff;
  cursor: pointer;
}
.header-btn2:hover {
  color: #d1d5db;
  box-shadow: 0 3px 8px 1px #9ca3af;
}
.menu {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .header-list {
    display: none;
  }
  .btn {
    display: none;
  }
  .menu {
    display: block;
    font-size: 25px;
    font-weight: 700;
  }
}

@media only screen and (max-width: 767px) {
  .header-container {
    width: 100%;
    height: fit-content;
    background: #fff;
    margin-right: 0px;
    margin-left: 0px;
    margin-top: 0px;
    top: 0;
    left: 0;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 0px;
    padding-left: 0px;
    position: fixed;
  }
  header {
    width: 80%;
    padding: 15px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 0 0px 0.1px rgb(212, 210, 210);
  }
  .header-list {
    display: none;
  }
  .btn {
    display: none;
  }
  .menu {
    display: block;
    font-size: 25px;
    font-weight: 700;
  }
}
</style>
