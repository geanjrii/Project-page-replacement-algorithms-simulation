# Projeto de Simulação de Algoritmos de Substituição de Páginas
Este projeto consiste na implementação de três dos principais algoritmos de substituição de páginas estudados na disciplina de Sistemas Operacionais: FIFO (First In, First Out), OTM (Algoritmo Ótimo) e LRU (Least Recently Used ou Menos Recentemente Utilizado).

O programa lê de um arquivo um conjunto de números inteiros, onde o primeiro número representa a quantidade de quadros de memória disponíveis na RAM e os demais representam a sequência de referências às páginas, sempre um número por linha. Em seguida, o programa simula o funcionamento dos três algoritmos de substituição de páginas e imprime o número de faltas de página obtido com a utilização de cada um deles.

## Algoritmos Implementados
## FIFO (First In, First Out)
O algoritmo FIFO é um algoritmo simples e fácil de implementar. Ele consiste em manter uma fila de páginas na ordem em que elas chegaram na memória. Quando uma nova página precisa ser carregada na memória e não há espaço disponível, a página mais antiga na fila é removida para dar lugar à nova página.

## OTM (Algoritmo Ótimo)
O algoritmo OTM é um algoritmo de substituição de páginas ideal, mas impraticável na maioria das situações reais. Ele substitui a página que será referenciada mais tarde no futuro, minimizando o número de faltas de página. No entanto, é difícil determinar qual página será referenciada no futuro.

## LRU (Least Recently Used)
O algoritmo LRU substitui a página que não foi referenciada há mais tempo. Ele utiliza uma lista de páginas ordenada do mais antigo para o mais recente, com a página mais antiga no início da lista. Quando uma nova página precisa ser carregada na memória e não há espaço disponível, a página no início da lista é removida para dar lugar à nova página.
