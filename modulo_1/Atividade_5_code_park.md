# instrução
Na tabela em anexo, encontramos dados de 4 jogadores de um game que contemplam os pontos e moedas obtidos durante as partidas e se conseguiram lutar ou não com o chefe.

Baseado nos dados desses jogadores, foram construídas algumas expressões. Avalie cada expressão abaixo, observando as condições de cada jogador, descrito na tabela acima. Marque com V( Verdadeiro) ou F(Falso) o resultado de cada expressão.

Dica: Lembre-se de substituir as variáveis "pontos", "moedas" e "enfrentou_chefe" pelos valores correspondentes para cada jogador.

Expressões:

(   )Jogador 1: (pontos >= 100) and (moedas >= 5) and (enfrentou_chefe == Sim)

(   )Jogador 2: (pontos >= 100) and (moedas >= 5) and (enfrentou_chefe == Não)

(   ) Jogador 3: (pontos < 100) or (moedas < 5) or (enfrentou_chefe == Sim)

(   ) Jogador 4: (pontos != 100) or (moedas != 5) or not(enfrentou_chefe == Não) 

![image](https://github.com/rogerdox/fap_softex/assets/116037752/f10a312a-3398-46c3-989b-9aae99f3c0b8)

# Resposta

( V )Jogador 1: (120 >= 100) and (15 >= 5) and (Sim == Sim) Para ser verdadero todos tem que ser verdadeiros pois são and nesse caso isso ocorre

( F )Jogador 2: (99 >= 100) and (200 >= 5) and (Não == Não) Para ser verdadero todos tem que ser verdadeiros mas a primeira expressão pois são and

( V ) Jogador 3: (100 < 100) or (5 < 5) or (Sim == Sim) Para ser verdadero basta uma ser verdadeiro pois é or sendo assim como a última expressão é vedadeira nesse caso isso ocorre

( V ) Jogador 4: (101 != 100) or (4 != 5) or not(Não == Não) Para ser verdadero basta uma ser verdadeiro pois é or sendo assim como apenas a última expressão não é vedadeira a resposta é verdade
