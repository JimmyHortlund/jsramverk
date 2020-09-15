<template>
  <div id="app">
    <div class="nav_container">
      <div class="home_link">
        <router-link to="/">Home</router-link>
      </div>
      <div class="report_link">
        <router-link to="/reports">Reports</router-link>
      </div>
    </div>

    <transition name="router-anim" enter-active-class="animated fadeInDown">
      <router-view/>
    </transition>

  </div>
</template>

<style scoped>
.nav_container {
  border: solid rgb(167, 98, 41);
  position: absolute;
  text-align: center;
  background-color: rgb(255, 248, 237);
  width: 25%;
  height: 2000px;
}

.home_link a {
  text-decoration: none;
  color: #000;
}

.report_link a {
  text-decoration: none;
  color: #000;
}

.home_link:hover {
  text-decoration: underline;
}

.report_link:hover {
  text-decoration: underline;
}

.home_link {
  margin-top: 20%;
  margin-bottom: 1em;
  font-size: 50px;
}

.report_link {
  font-size: 50px;
  text-decoration: none;
}

.nav_links:hover {
  color: rgb(255, 255, 255);
}
@import "https://cdn.jsdelivr.net/npm/animate.css@3.5.1";

</style>
