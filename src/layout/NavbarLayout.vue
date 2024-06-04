<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>

<template>
  <header>
    <div class="container-search">
      <div class="search-icon">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="32"
          height="32"
          viewBox="0 0 256 256"
        >
          <path
            fill="currentColor"
            d="m226.83 221.17l-52.7-52.7a84.1 84.1 0 1 0-5.66 5.66l52.7 52.7a4 4 0 0 0 5.66-5.66M36 112a76 76 0 1 1 76 76a76.08 76.08 0 0 1-76-76"
          />
        </svg>
      </div>
      <div class="container-search-suggestion">
        <div class="container-icon">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
            <path
              fill="currentColor"
              width="32"
              height="32"
              d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z"
            />
          </svg>
        </div>
        <div class="container-key">Trần Huỳnh Tấn Phát</div>
      </div>
      <div class="container-search-suggestion">
        <div class="container-icon">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512">
            <path
              fill="currentColor"
              width="32"
              height="32"
              d="M384 96V320H64L64 96H384zM64 32C28.7 32 0 60.7 0 96V320c0 35.3 28.7 64 64 64H181.3l-10.7 32H96c-17.7 0-32 14.3-32 32s14.3 32 32 32H352c17.7 0 32-14.3 32-32s-14.3-32-32-32H277.3l-10.7-32H384c35.3 0 64-28.7 64-64V96c0-35.3-28.7-64-64-64H64zm464 0c-26.5 0-48 21.5-48 48V432c0 26.5 21.5 48 48 48h64c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48H528zm16 64h32c8.8 0 16 7.2 16 16s-7.2 16-16 16H544c-8.8 0-16-7.2-16-16s7.2-16 16-16zm-16 80c0-8.8 7.2-16 16-16h32c8.8 0 16 7.2 16 16s-7.2 16-16 16H544c-8.8 0-16-7.2-16-16zm32 160a32 32 0 1 1 0 64 32 32 0 1 1 0-64z"
            />
          </svg>
        </div>
        <div class="container-key">Fresher</div>
      </div>
    </div>
    <nav>
      <ul class="nav_links">
        <li>
          <RouterLink
            to="/"
            :class="{ 'nav_links-choosed': $route.matched[0].name == '' }"
            >About</RouterLink
          >
        </li>
        <li>
          <RouterLink
            to="/skills"
            :class="{ 'nav_links-choosed': $route.matched[0].name == 'skills' }"
            >Skills</RouterLink
          >
        </li>
        <li>
          <RouterLink
            to="/experience"
            :class="{
              'nav_links-choosed': $route.matched[0].name == 'experience',
            }"
            >Experience</RouterLink
          >
        </li>
        <li>
          <RouterLink
            to="/contact"
            :class="{
              'nav_links-choosed': $route.matched[0].name == 'contact',
            }"
            >Contact</RouterLink
          >
        </li>
      </ul>
    </nav>
  </header>
</template>
<style scoped>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  background-color: transparent !important;
}
li,
a {
  
  font-weight: 500;
  font-style: normal;
  font-size: medium;
  color: white;
  text-decoration: none;
  padding: 6px 10px;
}
header {
  display: flex;
  width: 100%;
  justify-content: space-between;
  align-items: center;
  padding: 30px 10%;
  position: absolute;
  top: 0;
  right: 0;
}
.container-search {
  padding: 10px;
  border-radius: 180px;
  border: 2px solid white;
  display: flex;
  gap: 20px;
}
.container-search .search-icon {
  width: 42px;
  height: 32px;
  padding: 0 10px 0 0;
  border-right: 2px solid white;
  color: white;
}
.container-search-suggestion {
  height: 32px;
  border-radius: 180px;
  background: white !important;
  padding: 5px;
  display: flex;
  justify-items: center;
}
.container-search-suggestion .container-icon {
  width: 22px;
  height: 22px;
  padding: 5px;
  color: white;
  background: black !important;
  border-radius: 180px;
  display: flex;
  justify-content: center;
}
.container-search-suggestion .container-key {
  font-weight: 400;
  font-style: normal;
  font-size: medium;
  color: black;
  margin: 0 20px 0 10px;
}
.nav_links {
  list-style: none;
}
.nav_links li {
  display: inline-block;
  padding: 0px 20px;
}
.nav_links li a {
  transition: all 0.1s ease 0s;
}
.nav_links li a:hover {
  border-bottom: 3px solid white;
  background: transparent;
  /* border-radius: 10px; */
}
.nav_links-choosed {
  border-bottom: 3px solid white;
  background: transparent;
}
</style>