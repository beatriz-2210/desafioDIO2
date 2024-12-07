let vitorias = 87;
let derrotas = 25;
let name = "Maria";

function somar(vitorias, derrotas) {

    return vitorias - derrotas;
} 

   let saldo = somar(vitorias, derrotas);
   let rank;
    if(saldo <= 10){
      rank = "ferro";
   }else if(saldo >=11 && saldo <=20){
      rank = "bronze";
   }else if(saldo >=21 && saldo <=50){
      rank = "prata";
   }else if(saldo >=51 && saldo <=80){
      rank = "ouro";
   }else if(saldo >=81 && saldo <=90){
      rank = "diamante";
   }else if(saldo >=91 && saldo <=100){
      rank = "lendário";
   }else if(saldo <= 101){
      rank = "imortal";
   }
        console.log(name +  " tem " + saldo + " vitórias e está no rank: " + rank );
     
