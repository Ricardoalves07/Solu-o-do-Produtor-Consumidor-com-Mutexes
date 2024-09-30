# Código Produtor-Consumidor em C com Threads

Este programa implementa o problema do Produtor-Consumidor utilizando threads, mutexes e variáveis de condição para sincronizar o acesso a um buffer compartilhado.

## Funcionalidades
O programa permite que um número definido de **produtores** e **consumidores** compartilhem um buffer com capacidade limitada. Os produtores geram números aleatórios e os colocam no buffer, enquanto os consumidores retiram esses números do buffer para consumi-los. O programa utiliza **mutexes** para garantir exclusividade de acesso ao buffer e **variáveis de condição** para controlar o fluxo, evitando a condição de corrida.


