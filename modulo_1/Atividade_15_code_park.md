# Instrução

Desenvolva um código que simule uma eleição com três candidatos.
- candidato_X => 889
- candidato_Y => 847
- candidato_Z => 515
- branco => 0

O código deve perguntar se deseja finalizar a votação depois do voto. Caso o número do voto não corresponda a nenhum candidato ou seja branco, ele deve ser tratado como nulo. Se for inserido um texto ao invés de número, o código deve retornar uma mensagem para votar novamente.

Quando a votação for finalizada, o código deverá mostrar o vencedor, aquele com o maior número de votos e, também, a quantidade de votos de cada candidato, os brancos e nulos. 

# Resolução
```j.s
function contabilizar(voto, vetor_votos){
  switch(voto){
    case 889:
      vetor_votos[0] += 1;
      break
    case 847:
      vetor_votos[1] += 1;
      break
    case 515:
      vetor_votos[2] += 1;
      break
    case 0:
      vetor_votos[3] += 1;
      break
    default:
      vetor_votos[4] += 1;
  }
  return vetor_votos
}

var candidato_X = 0;
var candidato_Y = 0;
var candidato_Z = 0;
var branco = 0;
var nulo = 0;
var vetor_votos = [candidato_X, candidato_Y, candidato_Z, branco, nulo]


while(true){
var voto = parseInt(prompt("Qual o número do candidato ? " ))
  
  if(!isNaN(voto)){
    vetor_votos = contabilizar(voto,vetor_votos)
    s =  prompt("Caso queira encerra a votação digite sim, caso contrario digite nao")
    
    if(s === "sim"){
      console.log(`candidato_X = ${vetor_votos[0]}`)
      console.log(`candidato_Y = ${vetor_votos[1]}`)
      console.log(`candidato_Z = ${vetor_votos[2]}`)
      console.log(`BRANCO = ${vetor_votos[3]}`)
      console.log(`NULO = ${vetor_votos[4]}`)
      break;
    }else{continue}
    
  }else{
    console.log("Insira um número valido")
  }
}
```
