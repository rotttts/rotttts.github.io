<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
@import url('https://fonts.googleapis.com/css?family=Sarpanch:900');

* {
    box-sizing: border-box;
}

$rotationAmt: -12;

#h1z1 {
  display: grid;
  grid-template-areas: ". . ." ". text ." ". . .";
  grid-template-rows: 1fr auto 1fr;
  grid-template-columns: 1fr auto 1fr;
  height: 100vh;
  width: 100vw;
  margin: 0;
  overflow: hidden;
  background-image: radial-gradient(circle, #333333, #222222);
}

.fa {
  padding: 20px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-youtube {
  background: #00120b;
  color: white;
}


.fa-instagram {
  background: #00120b;
  color: white;
}

.fa-reddit {
  background: #00120b;
  color: white;
}


body {
    font-family: Arial;
    background-repeat: no-repeat;
    background-size:100% 100vh;
    padding: 0px;
    margin: -9px;
}

body {
  text-align: center;
 }

#page-wrap {
     width: 900px;
     text-align: left;
     margin: 0 auto;
}

/* Header/Blog Title */
.header {
    padding: 30px;
    font-size: 40px;
    text-align: center;
    background: transparent;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
    float: left;
    width: 75%;
}

/* Right column */
.rightcolumn {
    float: left;
    width: 25%;
    padding-left: 20px;
}

/* Fake image */
.fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 20px;
}

.nero {
    background-color: #0b6e4f;
    widht: 100%;
    height: 100px;
    padding-top: 3px;
    padding-left: 10px;
    padding-right: 10px;
    padding-bot: 10px; 
    margin-top: 20px;
}

.nero1 {
    background-color: #0b6e4f;
    widht: 100%;
    height: 80px;
    padding-top: 3px;
    padding-left: 10px;
    padding-right: 10px;
    padding-bot: 10px; 
    margin-top: 20px;
}

p.serif {
    font-family: "Times New Roman", Times, serif;
}

/* Add a card effect for articles */
.card {
     background-color: white;
     border: 1px solid #0b6e4f;
     padding-top: 5px;
     padding-left: 15px;
     padding-right: 15px;
     padding-bot: 15px;     
     margin-top: 0px;
}

.card1 {
     background-color: white;
     border: 1px solid #0b6e4f;
     padding-top: 5px;
     padding-left: 15px;
     padding-right: 15px;
     padding-bot: 15px;
     margin-top: 0px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}


/* Footer */
.footer {
    padding: 20px;
    text-align: center;
    background: #3bc14a;
    margin-top: 20px;
    margin-left: -9px;
    margin-right: -9px;
    margin-bot: -15px;    
}

.footer-menu {
    width: 100%;
    height: auto;
    margin: auto;
    margin-top: 20px;
}

.footer-menu a {
    font-family: arial;
    font-size: 15px;
    font-weight: 600;
    color: #00120b;
    padding: 10px;
    text-transform: uppercase;
    text-decoration: none;
}

.footer * {
   box-sizing: content-box;
}

.btn {
    border: none;
    background-color: inherit;
    padding: 14px 28px;
    font-size: 26px;
    cursor: pointer;
    display: inline-block;
    float: left;
}

/* On mouse-over */
.btn:hover {background: #3bc14a;}

.success {color: white;}
.info {color: white;}
.warning {color: white;}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
    .leftcolumn, .rightcolumn {   
        width: 100%;
        padding: 0;
    }
}
</style>
</head>
<body     background="https://i.imgur.com/IgHik92.png" >

<div id="page-wrap">
 <div class="h1z1">
  <h2 style="transform: skew(#{$rotationAmt}deg) rotate(#{$rotationAmt}deg);
  grid-area: text;
  font-family: 'Sarpanch', sans-serif;
  font-size: 12vmin;
  margin: 0;
  padding: 30px;
  color: green;
  text-shadow: 1vmin 1vmin 0 #9acd32, -1vmin -1vmin 0 #00cc66;text-align: center;">La tana di giorgio</h2>
</div>
<div style="width:100%">
<button class="btn success" style="width:25%">Home</button>
<button class="btn info" style="width:25%">Red Post</button>
<button class="btn warning" style="width:25%">Contatti</button>
<button class="btn warning" style="width:25%">Coming</button>
</div>
<div class="row">
  <div class="leftcolumn">
      <div class="nero">
      <h2 style="color: white;">6/14 PBE Aggiornato: Nuove emote, Rift Rivals, Nuovo tema login e bilanciamenti!</h2>
      </div>
          <div class="card">
      <h5>Ultimo aggiornamento Giugno 16, 2018</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Some text..</p>
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    </div>
          <div class="nero">
      <h2 style="color: white;">Cosa vedremo nella patch 8.12,nuovo AATROX e tanti bilanciamenti!</h2>
      </div>
    <div class="card">
      <h5 style="color:#4e6e5d;">Aggiornamento del 12 Giugno 2018 </h5>
      <img src="https://www.chrismoon.co.uk/wp-content/uploads/2015/12/500px-Ford_Motor_Company_Logo.svg-480x200.png" alt="News PBE" width="100%" height="200px">
      <p class="serif">Bella raga e benvenuti nel ciclo del pbe che ci portarà alla patch 8.12 sul live server,alcune delle novità più importanti riguardano il rework di aatrox,buff vari per aiutari gli adc da critico tra cui riduzione costo per l'infinity edge...</p>
      <h2 style="color:#4d5057;"><a style="text-decoration: none;color:#4d5057;" href="https://www.surrenderat20.net/search/label/PBE/">CONTINUA A LEGGERE-></a></h2>
    </div>
    
  </div>
  <div class="rightcolumn">
     <div class="nero">
      <h2 style="color: white;">Ti vuoi iscrivere al PBE?</h2>
      </div>
          <div class="card1" style="padding-top: 10px;">
      <img src="https://lolstatic-a.akamaihd.net/frontpage/apps/prod/pbe-registration/it_IT/17cd0b5698a90c980c41ac6293a41ad6dd6044f8/assets/img/heimerdinger.jpg" alt="Immagine PBE" width="174px" height="100px">
      <p class="serif">Molto semplicemente andando <a style="text-decoration: none;" href="https://pbesignup.na.leagueoflegends.com/it_IT/pbe"> qui</a> e mandando la richiesta,per essere accettati è richiesto un livello di honor 3 o superiore e una fedina penale pulita MONKAS.</p>
    </div>
         <div class="nero1">
      <h2 style="color: white;">Vuoi Seguirci?</h2>
      </div>
      <div class="card1">
      <a href="https://discord.gg/sQvcxae">
            <img src="https://discordapp.com/assets/fc0b01fe10a0b8c602fb0106d8189d9b.png" alt="DISCORD" width="140px" height="50px">
            </a>
            <a href="https://discord.gg/sQvcxae">
            <img src="https://itsdcdn.com/resources/services/logowide/340/instagram.png" alt="INSTAGRAM" width="140px" height="50px">
            </a>
            <a href="https://www.youtube.com/user/aleoncinoBO">
            <img src="https://www.pianetacellulare.it/images/fotonews/2015/09/1443423782.jpg" alt="YOUTUBE" width="140px" height="50px">
            </a>
            </div>
         <div class="nero1">
      <h3 style="color: white;">Da dove prendiamo questi dati?</h3>
      </div>
          <div class="card1">
      <p class="serif">I dati sugli aggiornamenti inseriti sul pbe vengono presi dalla board di league of legends dedicata al pbe e dal sito <a style="text-decoration: none;" href="https://www.surrenderat20.net/">surrender@20<a> </p>
    </div>
  </div>
</div>
</div>


<div class="footer">
  <a href="https://www.youtube.com/user/aleoncinoBO" class="fa fa-youtube"></a>
  <a href="#" class="fa fa-instagram"></a>
  <a href="https://discord.gg/sQvcxae" class="fa fa-reddit"></a>
  <div class="footer-menu">
    <a href="#">Home</a>
    <a href="#">Red Post</a>
    <a href="#">Contatti</a>
  </div>
  <p>Grazie mille per aver visitato il sito e ricorda che ogni giorno vengono caricati gli ultimi aggiornamenti provenienti dal pbe e dai rioter!!!</p>
  <img src="http://i.imgur.com/2Q8TFof.png">
</div>



</body>
</html>
