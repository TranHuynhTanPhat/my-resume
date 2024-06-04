<template>
  <div class="wrapper">
    <div class="mobile-development-title">
      Mobile development with <span>Flutter</span>
    </div>
    <div class="mobile-development-body">

        <img src="@/assets/healthline-thumbnail.png" alt="mobile application" />
    </div>
  </div>
</template>
<style scoped>
.wrapper {
  
  
  display: grid;
  padding: 5% 0;
}
.mobile-development-title {
  text-align: center;
  color: white;
  font-size: 36px;
  font-weight: 600;
  text-transform: uppercase;
}
.mobile-development-title span {
  font-size: 36px;
  font-weight: 600;
  text-transform: uppercase;
  color: #53c5f8;
}
.mobile-development-body {
  margin: 50px 0;
  display: flex;
  justify-content: center;
}
.mobile-development-body img {
  width: 50%;
  padding: 0 50px;
}
</style>