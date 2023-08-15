# Instrução

Você deve criar três listas em JavaScript:

1. para guardar os nomes de dez pessoas;
2. para guardar as suas idades;
3. para guardar as suas cores favoritas.

Em seguida, imprima essas listas. Depois, faça algumas modificações, alterando uma cor e uma idade. Ao terminar, imprima novamente todas as informações das três listas.

# Resoução

```j.s
var nome = ["Miguel","Arthur","Gael","Heitor","Helena","Alice" ,"Theo","Laura","maria","rai"]

var idade = [1,2,3,4,5,6,7,8,9,10 ]

var cor =["azul","amarelo","verde","vermelho","preto","laranja" ,"azul","verde","amarelo","roxo"]

idade.forEach(function(idade){
  console.log(idade)
})

cor.forEach(function(cor){
  console.log(cor)
})

idade.splice(0,1,15)
cor.splice(0,1,"rosa")

idade.forEach(function(idade){
  console.log(idade)
})

cor.forEach(function(cor){
  console.log(cor)
})
```
