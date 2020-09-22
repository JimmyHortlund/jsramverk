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

      <h4>Forskningsfrågor:</h4>
      <p>
        RQ1: <br>
        Hur upplever föräldrar till barn i lågstadiet att VR (Virituell verklighet) <br>
        kan påverka deras skolgång så som, betyg, koncentrationsförmåga, inlärningsmöjlighet. <br>
        Vilka för och nackdelar anser barnens föräldrar att det finns med att införa <br>
        VR i klassrummen i så tidig ålder. <br>
        <br>
        RQ2: <br>
        Hur tror övre delen av ungdomarna, 18 - 25, respektive vuxna ,26 och uppåt, att <br>
        AI, (artificiell intelligens) kommer att påverka vårat samhälle i framtiden och <br>
        finns det några tydliga skillnader hur de yngre ställer sig till AI jämfört <br>
        med äldre männsikor?
      </p>

      <h4>Länk till Githubrepo:</h4>
      <a href="https://github.com/JimmyHortlund/jsramverk">Github</a>

      <h4>README:</h4>
      <p>
        # jsramverk-me-app <br>
        VUE <br>
        <br>
        ## Project setup <br>
        npm install <br>

        <br>
        ## Install Vue <br>

        npm install -g @vue/cli <br>
        <br>

        ## Check Vue version <br>
        vue --version <br>

        <br>
        # Update global Vue CLI paclage <br>
        npm update -g @vue/cli <br>

        <br>
        ## Create new Vue project in terminal <br>
        vue create name_of_project <br>

        <br>
        ## Create new Vue project in GUI <br>
        vue ui <br>

        <br>
        ### Compiles and hot-reloads for development <br>
        npm run serve <br>

        <br>
        ### Compiles and minifies for production <br>
        npm run build <br>

        <br>
        ### Lints and fixes files <br>
        npm run lint <br>

        <br>
        ### Customize configuration <br>
        See [Configuration Reference](https://cli.vuejs.org/config/). <br>
      </p>
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
