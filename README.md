# Cache Simulator

Este projeto consiste em um simulador de cache, em Python, que utiliza diferentes algoritmos
de substituição (LRU, LFU e FIFO) para gerenciar o armazenamento de arquivos em um cache de memória.

## Funcionalidades

- **Modo de Simulação:** Permite ao usuário simular o comportamento do cache e avaliar o desempenho dos diferentes algoritmos de substituição.
- **Acesso a Arquivos:** Permite ao usuário acessar arquivos, que são armazenados no sistema de arquivos e gerenciados pelo cache.
- **Algoritmos de Substituição Suportados:** LRU (Least Recently Used), LFU (Least Frequently Used) e FIFO (First In, First Out).

## Arquivos

- **main.py:** Contém o código principal do programa, incluindo a lógica de interação com o usuário e a integração dos algoritmos de cache.
- **simulacao.py:** Arquivo responsável por fornecer a funcionalidade de simulação.
- **cache.py:** Contém as implementações dos algoritmos de cache (LRU, LFU e FIFO).
- **1 a 100.txt:** arquivos dos textos com 1000 palavras cada.
