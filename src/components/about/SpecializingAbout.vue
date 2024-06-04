<template>
  <div class="wrapper">
    <div class="title">
      <div class="title-1">what i do</div>
      <div class="title-2">specializing in</div>
    </div>
    <div class="row">
      <div class="column">
        <div class="icon icon-container-1">
          <img
            class="icon-img"
            alt="mobile speciality"
            src="@/assets/mobile-speciality.png"
          />
        </div>
        <div class="content">
          <div class="content-title">mobile application</div>
          <div class="content-body">build mobile application with flutter</div>
        </div>
      </div>
      <div class="column">
        <div class="icon icon-container-2">
          <img
            class="icon-img"
            alt="mobile speciality"
            src="@/assets/web-speciality.png"
          />
        </div>
        <div class="content">
          <div class="content-title">web application</div>
          <div class="content-body">
            using frameworks like Vuejs, Nuxtjs to program website interface
          </div>
        </div>
      </div>
      <div class="column">
        <div class="icon icon-container-3">
          <img
            class="icon-img"
            alt="mobile speciality"
            src="@/assets/design-speciality.png"
          />
        </div>
        <div class="content">
          <div class="content-title">design figma</div>
          <div class="content-body">
            experience using and designing with figma
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.wrapper {
  padding: 200px 5% 5% 5%;
  display: grid;
  gap: 50px;
  
}
.title {
  text-align: center;
}
.title-1 {
  font-weight: 500;
  color: #4275fa;
  text-transform: uppercase;
  font-size: 24px;
}
.title-2 {
  color: white;
  font-weight: 600;
  text-transform: capitalize;
  font-size: 36px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
.column {
  float: left;
  width: 33.33%;
  padding: 0 20px;
  position: relative;
}
.icon {
  padding: 10px;
  border-radius: 30px;
  width: 150px;
  height: 150px;
  display: flex;
  align-items: center;
  position: absolute;
  top: 0;
  left: 80px;
}
.icon-container-1 {
  background: rgb(229, 143, 58);
  background: -moz-linear-gradient(
    90deg,
    rgba(229, 143, 58, 1) 0%,
    rgba(57, 58, 61, 1) 100%
  );
  background: -webkit-linear-gradient(
    90deg,
    rgba(229, 143, 58, 1) 0%,
    rgba(57, 58, 61, 1) 100%
  );
  background: linear-gradient(
    90deg,
    rgba(229, 143, 58, 1) 0%,
    rgba(57, 58, 61, 1) 100%
  );
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#e58f3a",endColorstr="#393a3d",GradientType=1);
}
.icon-container-2 {
  background: rgb(221, 158, 146);
  background: -moz-linear-gradient(
    90deg,
    rgba(221, 158, 146, 1) 0%,
    rgba(137, 80, 202, 1) 100%
  );
  background: -webkit-linear-gradient(
    90deg,
    rgba(221, 158, 146, 1) 0%,
    rgba(137, 80, 202, 1) 100%
  );
  background: linear-gradient(
    90deg,
    rgba(221, 158, 146, 1) 0%,
    rgba(137, 80, 202, 1) 100%
  );
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#dd9e92",endColorstr="#8950ca",GradientType=1);
}
.icon-container-3 {
  background: rgb(254, 218, 132);
  background: -moz-linear-gradient(
    90deg,
    rgba(254, 218, 132, 1) 0%,
    rgba(127, 214, 245, 1) 100%
  );
  background: -webkit-linear-gradient(
    90deg,
    rgba(254, 218, 132, 1) 0%,
    rgba(127, 214, 245, 1) 100%
  );
  background: linear-gradient(
    90deg,
    rgba(254, 218, 132, 1) 0%,
    rgba(127, 214, 245, 1) 100%
  );
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#feda84",endColorstr="#7fd6f5",GradientType=1);
}
.icon-img {
  height: 100px;
}
.content {
  padding: 100px 30px 20px 30px;
  margin: 80px 0 0 0;
  border-width: 2px;
  border-color: white;
  border-style: solid;
  border-radius: 0 50px 0 0;
  height: 250px;
  display: block;
}
.content-title {
  color: white;
  font-weight: 600;
  font-size: 24px;
  text-transform: capitalize;
}
.content-body {
  color: white;
  font-weight: 400;
  font-size: 18px;
  text-align: justify;
}
</style>