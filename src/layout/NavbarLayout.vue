<template>
  <header>
    <nav>
      <ul class="nav_links">
        <li><a href="#">About</a></li>
        <li><a href="#">Skills</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>
<style scoped>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  background-color: transparent;
}
li,
a {
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  font-style: normal;
  font-size: medium;
  color: white;
  text-decoration: none;
  padding: 6px 10px;
}
header {
  display: flex;
  justify-content: right;
  align-items: center;
  padding: 30px 10%;
  position: absolute;
  top: 0;
  right: 0;
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
  border-style: none none solid none;
  border-width: 3px;
  background: transparent;
  /* border-radius: 10px; */
}
</style>