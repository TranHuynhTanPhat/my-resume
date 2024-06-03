<script setup>
</script>

<template>
  <div class="wrapper">
    <img
      alt="background header"
      class="background-header"
      src="@/assets/bg-hero.png"
    />
    <div class="greet">
      <div class="noto-sans-greet">HELLO, IM PHÁT</div>
      <div class="career">frontend/mobile developer</div>
      <div class="summary">
        Senior at HCMC University of Technology and Education – HCMUTE,
      </div>
      <div class="summary">less than 1 year experience.</div>
      <button class="hire">Hire me</button>
      <button class="get-cv">Get Cv</button>
    </div>
    <img
      alt="developer"
      class="image-developer"
      src="@/assets/developer-1.png"
    />
  </div>
</template>
<style scoped>
.wrapper {
  font-family: "Poppins", sans-serif;
}
.background-header {
  width: 100%;
}
.greet {
  position: absolute;
  top: 35%;
  left: 5%;
  color: white;
}
.career {
  font-size: 48px;
  font-weight: bold;
  text-transform: uppercase;
}
.summary {
  font-size: 18px;
  font-weight: 500;
}
.noto-sans-greet {
  font-family: "Noto Sans", sans-serif !important;
  font-optical-sizing: auto;
  font-weight: 600;
  font-style: normal;
  font-variation-settings: "wdth" 100;
  font-size: 24px;
  text-transform: uppercase;
}
button {
  padding: 10px 32px;
  border-radius: 180px;
  border-width: 0px;
  font-size: 18px;
  font-weight: 500;
  font-style: normal;
  margin: 20px 0 0 0;
}

button.hire {
  background: white;
  color: #3f32d0;
  border-width: 5px;
  border-color: white;
}
button.get-cv {
  color: white;
  background: transparent;
  border: solid;
  border-width: 5px;
  border-color: white;
}
.image-developer {
  width: 50%;
  position: absolute;
  right: 5%;
  top: 30%;
}
</style>