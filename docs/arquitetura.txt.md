# Arquitetura

* As funções relacionadas ao gerenciamento das casas do jogo da veha ficarão no módulo **jogovelha.py**

* O estado de cada casa do jogo será representada por uma string: "." para casa vazia; "X" para casa ocupada pelo 1º jogador, "0" para a casa ocupada pelo 2º jogador. 

* A função inicializar () retornará uma lista 3x3, onde cadaposição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias. 