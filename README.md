# Multiplicação de Matrizes pelo Método Strassen

Este código realiza a três tipos de multiplicação de matrizes sequenciais:
- Multiplicação pelo Método Strassen.
- Multiplicação usando a biblioteca Numpy.
- Multiplicação pelo forma tradicional.


A intenção é comparar os tempos de cada um dos métodos, para posteriormente realizar a distribuição pelo método mais otimizado.

Volker Strassen publicou o algoritmo de Strassen em 1969. Apesar de seu algoritmo ser apenas um pouco mais rápido do que o método padrão para a multiplicação de matrizes, ele foi o primeiro a observar que a abordagem usual não é ótima.

Sabe-se que o método do Strassen perde em tempo de execução para matrizes extremamente grandes.

Observações do Código:

- O Algoritmo Distribuido ainda não está utilizável.
- Independente do tamanho da matriz o algoritmo de Strassen sempre perde em tempo para os outros dois métodos.
- Ainda estuda-se entender o motivo da perda de desempenho por parte da implementação do Strassen.
