# Instrução

Um aluno do ensino fundamental precisa fazer como tarefa de casa a tabuada de alguns números inteiros, como nos exemplos em anexo.

Para ajudar esse aluno, você deve elaborar um algoritmo que solicite que seja digitado um número inteiro e que no final imprima o resultado da tabuada desse número.

![image](https://github.com/rogerdox/fap_softex/assets/116037752/79838733-7ab3-46d3-8ad2-377e98d35763)

# Resolução
```.js
numero = prompt('Digite um número para visualizar sua tabuada: ')
console.log('Tabuada do ', numero)
contador = 1

while(contador < 11){
  console.log(contador, 'x', numero, '=', contador*numero)
  contador += 1
}
```
