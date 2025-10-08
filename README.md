# projetos-curso-tema-3


Jogo de Comparação de Cartas
Descrição

Este é um jogo de cartas inspirado em jogos de “Super Trunfo”, onde cada carta representa uma cidade com atributos como população, área, PIB, pontos turísticos, PIB per capita, densidade populacional e um superpoder calculado.

O usuario ainda no menu principal escolhe o modo de jogo

Comparacao unica ou Comparacao multipla

Comparacao unica
O jogador escolhe 1 atributo para comparar entre duas cartas e o vencedor é definido com base em quem possui o melhor valor nesse atributo.

Comparacao multipla:
O jogador escolhe 3 atributos para comparar entre duas cartas e o vencedor é definido com base em quem possui os melhores valores nesses atributos.

Como Funciona

O jogador entra com os dados de duas cartas:

Estado

Código

Nome da cidade

População

Área

PIB

Número de pontos turísticos

O programa calcula automaticamente:

PIB per capita

pibpc = PIB * 1_000_000_000 / populacao;


Densidade populacional

densipop = populacao / area;


Super poder

superpoder = populacao + area + PIB + pibpc + (1 / densipop);

O jogador escolhe 1 ou 3 atributos para comparar( depende do modo de jogo escolhido):

População

Área

PIB

Número de pontos turísticos

PIB per capita

Densidade populacional

Super poder

O programa verifica se nenhum atributo foi repetido.

O programa compara 1 ou os 3 atributos escolhidos (dependendo do modo de jogo):

Cada atributo vencido soma 1 ponto para o jogador correspondente.

Ao final, o programa exibe:

Comparacao unica:
Carta 1 vence, e mostra a comparacao entre as duas
ou
Carta 2 vence, e mostra a comparacao entre as duas

Comparacao multipla:
Jogador 1 venceu

Jogador 2 venceu

Empate

Opcional: o usuário pode visualizar os detalhes completos das cartas.
