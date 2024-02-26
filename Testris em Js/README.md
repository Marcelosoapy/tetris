# tetris

Desafio de Futebol:
Funcionamento Geral:

O desafio de futebol foi integrado ao jogo Tetris que você possui.
Durante o jogo, há uma chance de 5% a cada peça que cai de encontrar um jogador de futebol.
Se um jogador de futebol for encontrado, o jogador receberá um aviso de que encontrou um jogador de futebol e receberá um bônus de 50 pontos.
Implementação:

A implementação desse desafio envolve adicionar uma função checkFootballPlayerBonus() que é chamada sempre que uma peça de tetromino se torna fixa no tabuleiro (ou seja, quando ela não pode mais ser movida para baixo).
Dentro dessa função, é gerado um número aleatório entre 1 e 100. Se esse número for menor ou igual a 5 (o que representa uma chance de 5%), então um jogador de futebol é considerado encontrado.
O jogador recebe um alerta informando que encontrou um jogador de futebol e é concedido um bônus de 50 pontos à pontuação atual.
Integração com o Jogo:

O bônus de jogador de futebol foi integrado ao jogo sem alterar a jogabilidade principal do Tetris. Ele adiciona um elemento de surpresa e recompensa durante o jogo.
Customização:

Você pode personalizar a probabilidade de encontrar um jogador de futebol ajustando o valor na função checkFootballPlayerBonus() (no momento, está configurado para 5% de chance).
Além disso, você pode modificar o valor do bônus concedido ao jogador ao encontrar um jogador de futebol.
