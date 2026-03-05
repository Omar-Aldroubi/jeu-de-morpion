# 🎮 Jeux de Morpion & Nim (Java)

Ce projet propose une implémentation complète du jeu de Morpion (Tic-Tac-Toe) et du jeu de Nim en Java. Il intègre une logique d'intelligence artificielle simple capable de détecter les cas gagnants pour empêcher l'adversaire de remporter la partie.

## 👥 Auteurs
Projet réalisé par **Khalil Mohammad** et **Omar Aldroubi**.

---

## 🏗️ Architecture et Exécution

Le projet est structuré en plusieurs packages pour séparer la logique de base, les versions factorisées (optimisées via l'héritage) et les jeux génériques. L'application est couverte par des tests unitaires.

### 📦 Package `games.nim`
* `games.nim.DemoNim` : Permet de jouer une partie de Nim à 2 joueurs.
* `games.nim.TestNim` : Lance les tests unitaires sur la classe Nim.

### 📦 Package `games.tictactoe`
* `games.tictactoe.DemoTicTacToe` : Permet de jouer au jeu de Morpion.
* `games.tictactoe.TestTicTacToe` : Lance les tests unitaires sur la classe TicTacToe.

### 📦 Package `games.factoredgames`
*Ce package contient les versions optimisées des jeux (factorisation du code).*
* `games.factoredgames.DemoNim` : Version optimisée du jeu de Nim.
* `games.factoredgames.DemoTicTacToe` : Version optimisée du jeu de Morpion.
* `games.factoredgames.TestAbstractGame` : Lance les tests sur la classe parente `AbstractGame`.
* `games.factoredgames.TestNimEtTicTacToe` : Lance les tests sur les classes factorisées.
* `games.factoredgames.TestTicTacToeWithHints` : Lance les tests sur la version du Morpion incluant le système d'indices (IA).

### 📦 Package `games.genericgames`
* `games.genericgames.DemoNim` : Démonstration générique de Nim.
* `games.genericgames.DemoTicTacToe` : Démonstration générique du Morpion.
* `games.genericgames.TestGenericGames` : Lance les tests sur l'ensemble des classes de ce package.

---
*Développé dans le cadre de notre apprentissage de la Programmation Orientée Objet en Java.*
