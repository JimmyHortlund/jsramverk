<template>
  <div class="home_container">
    <div class="home_title">
      <img height= 80px class="logo" alt="Vue logo" src="../assets/jsf.jpg">
      <div class="title_text">
        <h2>Reports</h2>
      </div>
    </div>

    <div class= "about_me_text">
      <h2>Week 1</h2>
      <a href="https://github.com/JimmyHortlund/jsramverk/blob/master/README.md">README at Github</a>
    </div>

  </div>
</template>

<style  scoped>
.home_container {
  border: solid rgb(167, 98, 41);
  background: rgb(255, 248, 237);
  padding: 3em;
  border-radius: 10px;
  color:rgb(31, 31, 31);
  width: 60%;
  margin-left: 30%;
}

.home_title {
  display: flex;
  align-items: center;
  background: rgb(167, 98, 41);
  border-radius: 10px;
}

.logo {
  border: 1px solid #acacac;
  border-radius: 50%;
}
.title_text p {
  margin-bottom: 0;
  margin-left: 1em;
  color: rgb(0, 0, 0);
}

.title_text h2 {
  margin-left: 0.5em;
  text-align: center;
}

.about_me_text p {
  line-height: 1.5;
  margin: 30 auto;
}
</style>
