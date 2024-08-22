body {
  background-color: #c7b8ea; /* light purple */
}

#text {
  background-color: #ffffff; /* white */
  color: #000000; /* black */
  padding: 10px;
}

#game {
  max-width: 500px;
  max-height: 400px;
  background-color: #ffffff; /* white */
  color: #000000; /* black */
  margin: 30px auto 0px;
  padding: 10px;
}

#controls, #stats {
  border: 1px solid #c7b8ea; /* light purple */
  padding: 5px;
  color: #c7b8ea; /* light purple */
}

#monsterStats {
  display: none;
  border: 1px solid #c7b8ea; /* light purple */
  padding: 5px;
  color: #ffffff; /* white */
  background-color: #c70d0d; /* dark red */
}

.stat {
  padding-right: 10px;
}

button {
  cursor: pointer;
  color: #c7b8ea; /* light purple */
  background-color: #feac32; /* orange */
  background-image: linear-gradient(#fecc4c, #ffac33);
  border: 3px solid #feac32; /* orange */
}// script.js
let xp = 0;
let health = 100;
let gold = 50;

document.getElementById("xpText").innerHTML = xp;
document.getElementById("healthText").innerHTML = health;
document.getElementById("goldText").innerHTML = gold;

document.getElementById("button1").addEventListener("click", findPrincess);
document.getElementById("button2").addEventListener("click", exploreCastle);
document.getElementById("button3").addEventListener("click", fightDragon);

function findPrincess() {
  // code to find the princess
}

function exploreCastle() {
  // code to explore the castle
}

function fightDragon() {
  // code to fight the dragon
}
