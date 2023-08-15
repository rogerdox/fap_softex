# Instruções do projeto

Nesta atividade, você deve criar um código em JavaScript com uma matriz bidimensional para armazenar informações sobre animais e as suas características.

Cada linha deve representar um animal e cada coluna terá as diferentes informações sobre ele, como nome, espécie e idade.

Realize essa atividade, suba esse arquivo em um drive com link público e compartilhe o link no campo ao lado para que outros desenvolvedores possam analisá-lo.

# Resolução

```j.s
var animal = [
  ["vaca", "pretinha", 5],
  ["cachorro", "bobe", 4],
  ["gato", "leãozinho", 12]
];

for (var i = 0; i < animal.length; i++) {
  console.log(animal[i].join("\t"));
}
```
