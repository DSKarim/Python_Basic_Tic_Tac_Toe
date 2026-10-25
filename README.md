<h1 align="center">❌⭕ Tic-Tac-Toe</h1>

<p align="center"><em>Le morpion classique, version terminal. Deux joueurs, un plateau, zéro dépendance.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3" />
  <img src="https://img.shields.io/badge/d%C3%A9pendances-aucune-success?style=for-the-badge" alt="Aucune dépendance" />
  <img src="https://img.shields.io/badge/projet%20d%27apprentissage-ff69b4?style=for-the-badge" alt="Projet d'apprentissage" />
</p>

---

## ✨ Pourquoi tu vas l'adorer

- **Zéro installation** : seule la bibliothèque standard de Python est utilisée.
- **Règles complètes** : victoire en ligne, colonne ou diagonale, et détection du match nul.
- **Saisie blindée** : coordonnées invalides ou case déjà prise ? Le jeu te le signale et te redemande.

## 🎮 Comment jouer

Chaque joueur indique une case avec deux chiffres, **colonne puis ligne**, de `1` à `3` :

| Saisie | Case |
|:---:|---|
| `1 1` | Coin inférieur gauche |
| `2 2` | Centre |
| `3 3` | Coin supérieur droit |

X commence, puis les joueurs alternent avec O. Le premier alignement de trois gagne !

## 🚀 Lancer la partie

```bash
python3 Code_Python_Basic_Tic_Tac_Toe
```

## 🕹️ Exemple de partie

Fin de partie : X réussit la diagonale.

```text
Enter the coordinates:3 3
---------
| O _ X |
| _ X _ |
| X _ O |
---------
X wins
```

## 🧠 Sous le capot

- Le plateau est stocké dans une **chaîne de 9 caractères**, convertie en matrice 3×3 pour vérifier les alignements.
- Chaque type de victoire a sa fonction : `check_line`, `check_column`, `check_diagonal`.
- Une boucle de jeu alterne les joueurs et redemande la saisie tant qu'elle est invalide.

## 🔭 Pistes d'évolution

- Ajouter un adversaire IA (le projet suivant s'en charge !).
- Proposer une nouvelle partie à la fin, sans relancer le programme.

---

<p align="center"><sub>Fait avec ❤️ et Python par DSKarim</sub></p>
