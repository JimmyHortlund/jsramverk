<template>
  <div class="home_container">
    <div class="home_title">
      <img height= 80px class="logo" alt="Vue logo" src="../assets/jsf.jpg">
      <div class="title_text">
        <p>About Me</p>
        <h2>Jimmy Hortlund</h2>
      </div>
    </div>

    <div class= "about_me_text">
      <p> Mitt namn är Jimmy Hortlund, jag är 40 år gammal och bor på Lidingö.
        Jag är född och uppvuxen i Jävre som är en liten by ca 2 mil söder
        om Piteå men pga av familjeskäl bor jag nu, sen början av 2019, på Lidingö
        nära min 7 åriga dotter och ex-fru och trivs jättebra här.
      </p>
      <p>
          Under min uppväxt spelade jag en hel del basket, innebandy och fotboll på
          min fritid, annars hängde man mycket ute och umgicks med kompisar, körde
          moped på sommaren och skoter på vintern.
          Jag gillade även att spela tv- och datorspel, Nintendo 8-bitar och Amiga 500
          var de maskinerna jag spelade mest på.
          <br>
          Efter ett tag började jag också utveckla
          ett väldigt stort intresse för musik, lärde mig spela gitarr och startade
          kort därefter ett metal-band med min kompis. Vi spelade in en skiva på
          musikhögskolan i Piteå, där jag praoade, men mycket mer än så blev det inte.
          <br>
          Jag lyssnade, och lyssnar fortfarande, på väldigt mycket musik, främst hårdrock
          och metal, några favoritband är tex. Metallica, Guns n Roses, Wasp, Marduk,
          Dark funeral och Testamen.
      </p>
      <p>
          Under Gymnasiet gick jag VVS programmet och hade tänkt bli rörmokare, inte
          för att jag var speciellt intresserad av det men mest för att min yrkesvägledare
          på skolan sa att det kommer finnas massor med jobb innom det yrket. Jag tappade intresset
          helt för att kröka rör och blev aldrig någon rörmokare, istället började jag jobba som
          tunnbrödsbagare, då jag behövde ett snabbt jobb, där blev jag kvar några år, sedan
          fick jag ett jobb på ett bageri/konditori i Piteå som bagare/konditor och där jobbade
          fram till att jag flyttade till Lidingö nu 2019.
      </p>
      <p>
          Jag har väl aldrig egentligen gillat att baka så, men det var ett jobb som gav pengar
          och en trygghet, men tillslut kände jag att, nej! nu får det vara nog, jag ska jobba
          så många år till och då vill jag göra något jag tycker är roligt och utvecklande. Då fanns
          det två allternativ, Musik eller Datorer, och ser man till jobbmarknade blev det ett lätt val, så
          nu sitter jag här och ska förhoppningsvis bli en webbprogrammerare och sluta slösa på mitt liv :)
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
  margin-top: 0;
}

.about_me_text p {
  line-height: 1.5;
  margin: 30 auto;
}
</style>
