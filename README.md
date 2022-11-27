# ai_frozenlake-GustavoMBorges
ai_frozenlake-GustavoMBorges created by GitHub Classroom

**Nome:** Gustavo Marques Borges

## Introdução

Foi proposto como desafio a pergunta "Qual é a configuração ideal do algoritmo Q-Learning para o problema do FrozenLake?", tendo em vista isso como objetivo. Foi implementado Q-Learning para o ambiente frozen lake em um mapa 4x4 e 8x8, como algoritimo de reinforcement learning.

## método de escolha dos melhores hiperparâmetros

O método utilizado foi o força bruta ou busca exaustiva para a escolha dos parametros, gerando todas as combinações possíveis dentro do range de valores escolido.

## forma de avaliação

A forma que foram avaliados todas as combinações de hiperparâmetros segue a sequencia de treinar o algoritimo e ser testado repetidas vezes (no caso 100),para estabelecer um scrore de quantas vezes ele atingiu o obvjetivo.

## forma de escolha
A escolha dos hiperparâmetros é definida baseada na medida "Rewards",previamente estabelecida, sendo que se busca maximiza-la ou obter uma eficiencia de pelo menos 80%

## Resultados em Graficos

Para o ambiente 4 x 4 

Para o ambiente 8 x 8

## Resultados

Para o ambiente 4 x 4 
- **Alpha:** 0.5
- **Gamma:** 0.9
- **Epsilon:** 0.8
- **Epsilon Mínimo:** 0.0001
- **Decaimento do Epsilon:** 0.9999
- **Número de Epsodios:** 9000

Para o ambiente 8 x 8

## Discutindo resultados

Obiviamente não se pode confiar totalmente no método da força brutra que tem como seu limitante maior o Hardware disponivel.No entanto ele pode servir como norte em questão de inicio de procura.
