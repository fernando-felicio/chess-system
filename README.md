# ChessGame 

Este é um projeto de implementação de um jogo de xadrez em Java, dividido em vários pacotes e classes para representar as peças, o tabuleiro e a lógica do jogo.

## Pacote `chess.pieces`

Este pacote contém as classes que representam as peças do jogo de xadrez:

- **`Bishop`**: Representa o bispo e implementa a lógica para calcular seus movimentos no tabuleiro.
- **`King`**: Representa o rei e implementa a lógica para calcular seus movimentos, incluindo o movimento especial "roque".
- **`Knight`**: Representa o cavalo e implementa a lógica para calcular seus movimentos.
- **`Pawn`**: Representa o peão e implementa a lógica para calcular seus movimentos, incluindo o movimento especial "en passant".
- **`Queen`**: Representa a rainha e implementa a lógica para calcular seus movimentos.
- **`Rook`**: Representa a torre e implementa a lógica para calcular seus movimentos.

## Outros pacotes e classes

- **Pacote `chess`**: Contém as classes principais relacionadas ao jogo de xadrez, como `ChessMatch`, `ChessPiece`, `ChessPosition` e `Color`.
- **Pacote `boardgame`**: Contém classes genéricas relacionadas ao tabuleiro de jogo, como `Board` e `Position`.

## Como Usar

1. Clone este repositório.
2. Compile o código-fonte Java.
3. Execute a classe principal para iniciar o jogo.

## Licença

Livre.

