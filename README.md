# Tic Tac Toe

Ce projet est un jeu Tic Tac Toe simple réalisé en HTML, CSS et JavaScript.

## Comment jouer

- Ouvrez le fichier `index.html` dans votre navigateur.
- Cliquez sur les cases pour placer votre marque (X ou O).
- Le premier joueur à aligner trois marques horizontalement, verticalement ou en diagonale remporte la partie.
- Si toutes les cases sont remplies sans alignement gagnant, la partie se termine en match nul.

## Structure du code

- Le plateau de jeu est représenté par une grille HTML avec des divs ayant la classe "cell".
- Lorsque vous cliquez sur une case, la fonction `makeMove(index)` est appelée pour placer la marque du joueur actuel.
- La fonction `checkWinner()` vérifie si le joueur actuel a remporté la partie en vérifiant toutes les conditions de victoire.
- La fonction `resetGame()` recharge la page pour réinitialiser le jeu.# tik-tak-toe-simple
