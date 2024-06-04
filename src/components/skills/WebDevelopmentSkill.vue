<template>
    <div class="wrapper">
      <div class="web-development-title">
        Web development with <span>VueJS And NuxtJS</span>
      </div>
      <div class="web-development-body">
          <img src="@/assets/api-dashboard-web-development.png" alt="api dashboard web application" />
          <img src="@/assets/podstreet-web-application.png" alt="podstreet web application" />
          <img src="@/assets/healthline-admin-web-aplication.png" alt="healthline admin web application" />
      </div>
    </div>
  </template>
  <style scoped>
  .wrapper {
    
    
    display: grid;
    padding: 5%;
  }
  .web-development-title {
    text-align: center;
    color: white;
    font-size: 36px;
    font-weight: 600;
    text-transform: uppercase;
  }
  .web-development-title span {
    font-size: 36px;
    font-weight: 600;
    text-transform: uppercase;
    color: #3fb883;
  }
  .web-development-body {
    margin: 50px 0;
    display: flex;
    justify-content: center;
  }
  .web-development-body img {
    width: 33.33%;
    padding: 0 50px;
  }
  </style>