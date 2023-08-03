# instrução

Levando em consideração os aprendizados sobre as estruturas condicionais, elabore um algoritmo que possa descobrir, através de perguntas e respostas, qual é o meio de transporte que o usuário está considerando. O usuário deverá escolher uma das seguintes opções:

- trator; 
- moto; 
- bicicleta. 

Para chegar ao resultado, as perguntas precisam ser respondidas apenas com "Sim" ou "Não".

Exemplo:

É terrestre? Sim.

Cabe apenas uma pessoa? Sim.

É pesado? Não.

Tem pedal? Sim.

Então, o transporte escolhido foi a bicicleta.

Para chegar ao resultado de cada uma das opções, use o modelo em abaixo.
![image](https://github.com/rogerdox/fap_softex/assets/116037752/b5c066d3-3fce-4023-a2d6-5b4816902fdc)

# resposta

```.js
terrestre = prompt('É terrestre? ')
cabe1 = prompt('Cabe apenas uma pessoa? ')
peso = prompt('É pesado? ')

if(terrestre == 'sim'){
  if(cabe1 == 'sim'){
    if(peso == 'sim'){
      console.log('É um trator')
    }else{
    console.log('É uma bicicleta')
  }
  }else{
    console.log('É uma moto')
  }
}else{
  console.log('Não é moto, bicicleta ou trator')
}
```
