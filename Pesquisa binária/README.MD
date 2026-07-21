01. Pesquisa Binária

Diário de estudos deste algoritmo. São anotações minhas enquanto aprendo, não uma referência formal.

O que é (com as minhas palavras)

Uma pesquisa binária é basicamente uma forma de achar um resultado numa lista ordenada cortando ela no meio, ou seja, eliminando metade das opções a cada tentativa. Ela só funciona se a lista estiver ordenada. Um exemplo é uma lista telefônica em ordem alfabética.

A função pega um array ordenado e um item. Se o item está no array, ela retorna a posição dele, e assim eu consigo saber em que ponto ele estava.

Como funciona passo a passo

A cada rodada eu olho o elemento do meio do trecho que ainda restou:

se ele for o item que procuro, achei
se ele for maior que o item, o item só pode estar na metade de baixo, então descarto a metade de cima
se ele for menor, descarto a metade de baixo

Repito isso até achar o item ou até não sobrar mais nada para olhar.

O que eu acrescentei

O livro mostra a busca retornando só o índice. Coloquei um contador de passos (contagem) para ver quantas tentativas o algoritmo leva até achar o número. Foi assim que consegui enxergar na prática a parte dos logaritmos.

Trecho central (o código completo está em pesquisa_binaria.py):