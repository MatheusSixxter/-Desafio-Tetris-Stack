# -Desafio-Tetris-Stack
Desafio Tetris Stack - Segundo Período - Estácio
# Tetris Stack 🧱

Versão **simplificada** do clássico Tetris, feita em **C** para console.  
Aqui, as peças são blocos 1x1 que caem em colunas escolhidas pelo jogador.  
O objetivo é empilhar blocos sem deixar o tabuleiro encher.


## 🕹️ Como funciona
- O tabuleiro tem **10 linhas x 5 colunas**.  
- Cada jogada, o jogador escolhe a coluna (0 a 4) onde o bloco deve cair.  
- Os blocos empilham do fundo para cima.  
- O jogo termina quando não há mais espaço no topo.  


## 🚀 Como compilar e rodar

### Linux/Mac
```bash
gcc tetris_stack.c -o tetris
./tetris
