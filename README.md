
//Criação de uma variavel para armazenar o nome e a quantidade de experiencia(XP) herói,
//  depois utilize uma estrutura de decisão uma estrutura de decisão para apresentar alguma das mensagens abaixo

// xp 0 <= 1000 "ferro"
// xp 1001 <= 2000 "bronze"
// xp 2001 <= 5000 "prata ouro"
// xp 5001 <= 8000 "platina diamante"
// xp 8001 <= 9000 "ascendente"
// xp 9001 <= 10000 "imortal"
// Xp 10001 < "radiante"

let nomeHeroi = "Blue";
let xpHeroi = 9650;
let nivelHeroi = "";

let nivel1= "ferro" (xpHeroi >=0 && xpHeroi <=1000);
let nivel2= "bronze" (xpHeroi >=1001 && xpHeroi <=2000);
let nivel3= xpHeroi >=2001 && xpHeroi <=5000;
let nivel4= xpHeroi >=5001 && xpHeroi <=8000;
let nivel5= xpHeroi >=8001 && xpHeroi <=9000;
let nivel6= xpHeroi >=9001 && xpHeroi <=10000;
let nivel7= xpHeroi >10000;

if(nivel1){
    nivelHeroi = "ferro";
}

