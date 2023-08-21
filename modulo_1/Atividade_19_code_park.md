# Instruções do projeto

Temos o array [15, 8, 10, 25, 12, 30, 5, 20, 18, 7] e precisamos criar um código em JavaScript para encontrar o valor 20.

Para isso, temos que escolher entre realizar uma busca linear ou binária de acordo com a que for mais adequada para essa situação.

Codifique a solução mais eficiente para buscar o número 20 no array.

Realize essa atividade, suba esse arquivo em um drive com link público e compartilhe o link no campo ao lado para que outros desenvolvedores possam analisá-lo.

# Resolução

```j.s
function busca(vetor, valor_a_ser_buscado){
  for(var i = 0; i < vetor.length; i++){
  if(vetor[i] === valor_a_ser_buscado){
    return i;
  }
}
}

vetor = [15, 8, 10, 25, 12, 30, 5, 20, 18, 7]
valor_a_ser_buscado = 20

indici = busca(vetor, valor_a_ser_buscado)
console.log(`O valor buscado esta no indici`, indici)
```
