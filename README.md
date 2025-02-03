# Bingo Game

## Descrição

Este é um jogo de Bingo implementado em C++. O programa gera cartelas de Bingo aleatórias, permite ao jogador escolher uma cartela e sorteia números até que o jogador complete sua cartela.

## Funcionalidades

- Geração de cartelas aleatórias (5x5) com números entre 10 e 75.
- Impressão formatada das cartelas.
- Sorteio de números aleatórios.
- Marcar números sorteados na cartela escolhida.
- Verifica se a cartela foi completada e declara o vencedor.

## Como executar

1. Compile o programa utilizando um compilador de C++, como `g++`:

   ```sh
   g++ bingo.cpp -o bingo
   ```

2. Execute o programa:

   ```sh
   ./bingo
   ```

## Estrutura do Código

O programa está estruturado da seguinte forma:

- ``: Representa um jogador com sua cartela e números sorteados.
- ``: Cria dinamicamente uma matriz para representar a cartela.
- ``: Preenche a cartela com números aleatórios.
- ``: Exibe a cartela formatada.
- ``: Verifica se um número está presente na cartela.
- ``: Verifica se todos os números foram marcados (jogo ganho).
- ``: Gerencia a execução do jogo, incluindo a escolha da cartela, o sorteio dos números e a verificação da vitória.

## Exemplo de Execução

```
|==========================================|
|==========================================|
|      B      I      N      G      O       |
|==========================================|
|==========================================|

--------------- CARTELA 01 ----------------
|  12  |  34  |  56  |  78  |  90  |
|  ... |  ... |  ... |  ... |  ... |
Escolha uma cartela [1 / 2]: 1
-> Voce esta jogando com a cartela 01.
Precione Enter para iniciar o sorteio...
- Foi sorteado o numero [34].
Precione Enter para continuar...
...
|======================================|
|==== Voce ganhou:  B  I  N  G  O  ====|
|======================================|
```

## Requisitos

- Compilador C++ (GCC, Clang, MSVC, etc.)
- Sistema operacional compatível com execução de binários C++

## Melhorias Futuras

- Adicionar suporte a múltiplos jogadores.
- Melhorar a interface do usuário com menus interativos.
- Permitir que o usuário escolha os números da sua cartela.
- Implementar um sistema de apostas e pontuação.

## Autor

Desenvolvido por Maria Eduarda da Nóbrega.

