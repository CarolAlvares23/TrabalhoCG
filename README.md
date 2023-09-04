# Trabalho de Computação Gráfica (Animação 2D)

# Snake Game

Este é um jogo simples do tipo Snake, desenvolvido em HTML e JavaScript. O jogo permite que o jogador controle uma cobra que deve comer comida sem colidir com obstáculos. A pontuação aumenta à medida que a cobra come mais comida, e o jogo continua até que a cobra colida com um obstáculo ou ultrapasse os limites do campo de jogo.

# Funcionalidades

- Controle da cobra com as teclas de seta do teclado.
- Comida aparece aleatoriamente no campo de jogo.
- Obstáculos são posicionados no campo.
- Pontuação aumenta quando a cobra come a comida.
- O jogo termina quando a cobra colide com um obstáculo ou ultrapassa os limites do campo de jogo.

# Pré-requisitos

Nenhum pré-requisito especial é necessário para executar o jogo,  basta abrir o arquivo HTML em um navegador da web compatível.

# Como Jogar

1. Abra o arquivo `index.html` em seu navegador.
2. Clique no botão "Start" para iniciar o jogo.
3. Use as teclas de seta do teclado para controlar a direção da cobra.
4. Tente comer a comida sem colidir com os obstáculos.
5. A pontuação aumenta cada vez que a cobra come a comida.
6. O jogo termina quando a cobra colide com um obstáculo ou ultrapassa os limites do campo de jogo.

# Funções do Código

1. **drawSnake()**: Desenha a cobra no campo de jogo. Ela percorre cada segmento da cobra e desenha uma imagem (representando a cobra) nas posições corretas.

2. **drawFood()**: Responsável por desenhar a comida no campo de jogo. A comida é representada como um quadrado rosa.

3. **drawObstacles()**: Desenha os obstáculos no campo de jogo. Os obstáculos são representados como quadrados cinza escuro.

4. **update()**: A função de atualização do jogo. Ela é responsável por atualizar a posição da cobra com base na direção atual, verificar se a cobra comeu a comida, atualizar a pontuação, lidar com colisões com obstáculos e verificar se a cobra ultrapassou os limites do campo de jogo.

5. **gameLoop()**: O loop principal do jogo. Ele limpa o conteúdo anterior do campo de jogo, atualiza a lógica do jogo chamando a função update e redesenha todos os elementos do jogo (cobra, comida e obstáculos) usando as funções de desenho.

6. **endGame()**: Encerra o jogo quando ocorre uma colisão com obstáculos ou quando a cobra ultrapassa os limites do campo de jogo. Exibe uma mensagem de fim de jogo com a pontuação final.

7. **Event Listener de Teclado**: O jogo responde a eventos de teclado para permitir que o jogador controle a direção da cobra. As teclas de seta são usadas para alterar a direção da cobra.




