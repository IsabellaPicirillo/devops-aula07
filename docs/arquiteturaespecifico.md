# Arquitetura
##Especificação da jogada
* As funções relacionadas as especificações das jogadas ficarão no módulo **especificaçoes.py**.
* O estado de cada casa do jogo será representada por uma string: "." para casa
vazia; "X" para casa ocupada pelo 1o jogador; "O" para casa ocupada pelo 2o
jogador

* Para realizar a jogada é necessario verificar se a casa já esta preenchida, retornando assim se o jogador pode ou não
realizar a jogada

* A função inicializar() retornará uma lista 3x3, onde cada posição conterá uma
string para indicar o estado de uma casa do jogo. A função retornará todas as
casas inicialmente vazias.

* A função jogar(jogador, linha, coluna) irá posicionar o **jogador** ('X' ou
'O') na posição definida por **linha** e **coluna**.
