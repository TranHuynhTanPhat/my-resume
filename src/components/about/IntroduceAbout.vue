<template>
  <div class="wrapper">
    <div class="row">
      <div class="column">
        <img alt="increase" src="@/assets/agile.webp" />
      </div>
      <div class="column">
        <img alt="developer" src="@/assets/developer-2.png" />
      </div>
      <div class="column">
        <div>
          <div class="about-me">about me</div>
          <div class="header-developer">frontend/mobile developer</div>
          <div class="introduce-developer">
            I am Tran Huynh Tan Phat, currently a senior student at HCMC
            University of Technology and Education – HCMUTE. I am passionate
            about web programming and mobile programming. I am willing to try
            new technologies and am not afraid to change myself to develop
            further.
          </div>
        </div>
        <div>
          <div class="hoppy-title">my hoppy</div>
          <div class="hoppy">
            <div class="hoppy-item">
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512">
                  <path
                    fill="#4275fa"
                    d="M192 64C86 64 0 150 0 256S86 448 192 448H448c106 0 192-86 192-192s-86-192-192-192H192zM496 168a40 40 0 1 1 0 80 40 40 0 1 1 0-80zM392 304a40 40 0 1 1 80 0 40 40 0 1 1 -80 0zM168 200c0-13.3 10.7-24 24-24s24 10.7 24 24v32h32c13.3 0 24 10.7 24 24s-10.7 24-24 24H216v32c0 13.3-10.7 24-24 24s-24-10.7-24-24V280H136c-13.3 0-24-10.7-24-24s10.7-24 24-24h32V200z"
                  />
                </svg>
              </div>
              <p>Game</p>
            </div>
            <div class="hoppy-item">
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                  <path
                    fill="#4275fa"
                    d="M482.3 192c34.2 0 93.7 29 93.7 64c0 36-59.5 64-93.7 64l-116.6 0L265.2 495.9c-5.7 10-16.3 16.1-27.8 16.1l-56.2 0c-10.6 0-18.3-10.2-15.4-20.4l49-171.6L112 320 68.8 377.6c-3 4-7.8 6.4-12.8 6.4l-42 0c-7.8 0-14-6.3-14-14c0-1.3 .2-2.6 .5-3.9L32 256 .5 145.9c-.4-1.3-.5-2.6-.5-3.9c0-7.8 6.3-14 14-14l42 0c5 0 9.8 2.4 12.8 6.4L112 192l102.9 0-49-171.6C162.9 10.2 170.6 0 181.2 0l56.2 0c11.5 0 22.1 6.2 27.8 16.1L365.7 192l116.6 0z"
                  />
                </svg>
              </div>
              <p>Travel</p>
            </div>
            <div class="hoppy-item">
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                  <path
                    fill="#4275fa"
                    d="M256 80C149.9 80 62.4 159.4 49.6 262c9.4-3.8 19.6-6 30.4-6c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48c-44.2 0-80-35.8-80-80V384 336 288C0 146.6 114.6 32 256 32s256 114.6 256 256v48 48 16c0 44.2-35.8 80-80 80c-26.5 0-48-21.5-48-48V304c0-26.5 21.5-48 48-48c10.8 0 21 2.1 30.4 6C449.6 159.4 362.1 80 256 80z"
                  />
                </svg>
              </div>
              <p>Music</p>
            </div>
            <div class="hoppy-item">
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                  <path
                    fill="#4275fa"
                    d="M362.7 19.3L314.3 67.7 444.3 197.7l48.4-48.4c25-25 25-65.5 0-90.5L453.3 19.3c-25-25-65.5-25-90.5 0zm-71 71L58.6 323.5c-10.4 10.4-18 23.3-22.2 37.4L1 481.2C-1.5 489.7 .8 498.8 7 505s15.3 8.5 23.7 6.1l120.3-35.4c14.1-4.2 27-11.8 37.4-22.2L421.7 220.3 291.7 90.3z"
                  />
                </svg>
              </div>
              <p>Design</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.wrapper {
  font-family: "Poppins", sans-serif;
  padding: 0 5%;
  margin: 200px 0 0 0;
}
/* Clear floats after the columns */
.row {
  content: "";
  display: flex;
  clear: both;
}
.column {
  float: left;
  width: 33.33%;
  margin-top: auto;
}
img {
  width: 100%;
}
.about-me {
  font-weight: 500;
  font-style: normal;
  color: #4275fa;
  font-size: 24px;
  text-transform: uppercase;
}
.header-developer {
  font-weight: 600;
  font-style: normal;
  font-size: 36px;
  text-transform: uppercase;
}
.introduce-developer {
  font-size: 18px;
  text-align: justify;
}
.hoppy-title {
  font-weight: 600;
  font-size: 24px;
  text-transform: uppercase;
  margin: 40px 0 10px 0;
}
.hoppy {
  display: flex;
  gap: 20px;
}
.hoppy p {
  font-weight: 600;
  font-size: 18px;
}
.icon {
  width: 32px;
  height: 32px;
  color: #4275fa;
}
.hoppy-item {
  display: flex;
  gap: 10px;
}
</style>