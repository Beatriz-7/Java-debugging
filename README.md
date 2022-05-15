# Java-debugging
Exercícios Dio/GFT Debugging-Java

# Debugging Java

Bugs = erros de programação

Debugging/depuração = processo de encontrar e corrigir bugs
 - é uma tarefa difícil e trabalhosa, variando de acordo com o ambiente de desenvolvimento e suas ferramentas disponível, como também a linguagem de programação 
 utilizada

## Tipos de erros

- Erros de sintaxe

  É um erro nas regras estabelecidas da linguagem:
  1. parênteses, chaves, colchetes que abrem mas não fecham
  2. duas instruções sem um ponto-e-vírgula entre elas
  3. uma palavra-chave sendo usada numa posição inesperada

- Erros de semântica

  É um erro na "lógica do código", em sua semântica, o código está sintaticamente correto, porém não faz o que se esperava dele.
  1. Tentar dividir um número por uma String ou por zero.
  2. Atribuir um valor incoerente a um tipo de dado.
  3. Tentar fechar um arquivo que não foi aberto.

## Depuração/Debugging

Linguagens de alto nível tornam a depuração mais fácil, pois fornecem mais ferramentas para identificar erros, como o tratamento de exceções.

Depuradores:
- funcionam assumindo o controle do tempo de execução de um programa e permitindo que você o observe e controle 
- Para fazer isso, ele mostra a pilha do programa e permite que você a atravesse em qualquer direção
- Quando você está em um depurador, obtém uma imagem mais completa de um quadro de pilha do que quando olha os rastreamentos de pilha em uma mensagem de log.

## Pilha de Execução de um Programa Java/Stack Trace

- Pilha de Execução:

Toda invocação de método é empilhada em uma estrutura de dados que isola a área de memória de cada um. Quando um método termina (retorna), ele volta para o método que 
o invocou.

- Stack Trace:

É a matriz onde encontramos a pilha de excecução da exceção. O rastreamento da pilha busca (rastreio) para a próxima linha onde a exceção pode surgir.

* ler de baixo para cima 
