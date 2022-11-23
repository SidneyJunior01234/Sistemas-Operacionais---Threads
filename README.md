# Sistemas Operacionais - Threads

## Sobre o projeto:
Esse projeto tem o objetivo de realizar simulações da memória cache utilizando threads, o mesmo faz parte do conjunto de avaliações da disciplina DCA0108 - SISTEMAS OPERACIONAIS da UFRN.

O programa inicial, que será a thread mãe, deverá realizar a leitura de um arquivo texto (nomeado enderecos.dat) e salvar suas informações em uma estrutura de dados adequada para o problema. Os dados lidos são, para efeitos de simulação de cache, uma listagem de endereços de uma memória de 16 K posições, os quais são acessados para operações de leitura. Estando, então, a thread mãe, com a estrutura de dados que representa os endereços, ela deve lançar quatro threads em que, cada uma, realizará uma simulação de cache diferente. As simulações e especificações são:
