<template>
  <div class="header">
    <div class="logo"><a href="index.html">Oblivion</a></div>
    <ul>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="works.html">Works</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
    <input type="checkbox" id="toggle_ham" style="display: none;" />
    <label for="toggle_ham" class="menu-trigger">
      <span></span>
      <span></span>
      <span></span>
    </label>
  </div>
</template>

<style lang="scss">
.logo {
  font-size: 45px;
  float: left;
  padding-left: 50px;
}
.header li {
  font-size: 30px;
  list-style: none;
  float: right;
  padding-top: 16px;
  padding-right: 30px;
  line-height: normal;
}
.header {
  position: fixed;
  background-color: #333;
  height: 75px;
  width: 100vw;
  line-height: 75px;
  color: #edf7f5;
  z-index: 0;
  top: 0%;
}

.header a:link,
.header a:visited,
.header a:hover,
.header a:active {
  text-decoration: none;
  color: #fff;
}

a:link,
a:visited,
a:hover,
a:active {
  color: #000;
}
</style>
