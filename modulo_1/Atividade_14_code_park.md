# Instrução

Desenvolva um programa que recebe do usuário nome completo e ano de nascimento que seja entre 1922 e 2021. A partir dessas informações, o sistema mostrará o nome do usuário e a idade que completou, ou completará, no ano atual (2022).

Caso o usuário não digite um número ou apareça um inválido no campo do ano, o sistema informará o erro e continuará perguntando até que um valor correto seja preenchido.

# Resolução

```j.s
nome = prompt('informe seu nome ')

while (true) {
data = prompt('informe sua data de nascimento ')
 
if((data > 1922) && (data < 2021)){
  idade = 2021 - data
  break
}else{
  console.log('Digite um valor valido ')
}}
console.log('Nome: ', nome)
console.log('numero: ', idade)
```
