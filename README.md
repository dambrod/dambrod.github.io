# Chronociné

Le jeu est accessible [ici](https://dambrod.github.io/) (Utiliser chrome de préférence)
![Capture d’écran 2023-06-11 191341](https://github.com/theor98/theor98.github.io/assets/100685679/0aab1b89-927a-4997-b879-f1d892464cbb)

## Descirption 

Durant le cours "Introduction à l'histoire du cinéma", donné par Alain Boillat, les étudiant·e·s visionnent plus de 200 séquences de films différents. Le corpus d'examen est constitué d'environ la moitié des films, soit une centaine. L'objectif de ce jeu est de permettre aux étudiant·e·s de vérifier leur capacité à dater correctement les films d'examen de manière ludique. Les joueur·euse·s doivent placer des films dans une frise chronologique en fonction des autres films déjà placés. Evidemment, plus le nombre de films déjà positionnés dans la frise chronologique est grand, plus le jeu devient difficile !

## Fonctionnalités 

Le jeu a été conçu pour placer jusqu'à 10 films dans la frise, une fois ce nombre atteint, tous les films disparaissent sauf un et le jeu continue. Un score comptabilise le nombre de films correctement positionnés et un highscore sauvegardé dans le stockage web local permet de conserver une trace de sa meilleure performance. Une fois la moindre erreur commise la partie s'arrête et les dates des films sont révélées aux joueur·euses. A ce moment, il est possible de cliquer sur les affiches des films pour ouvrir la page IMDb correspondante, ce qui permet de se renseigner facilement si les étudiant·es ne se souviennent plus du film. Le bouton "reset" permet de relancer une partie. Le jeu inclut également un tutoriel pour expliquer les actions à faire dans les premiers moments de la partie.
![image](https://github.com/theor98/theor98.github.io/assets/100685679/da67a3de-3c86-41e7-8f2d-0ab2e4825aa0)


## Dataset

Le jeu permet de jouer avec 95 des 96 films que les étudiant·es en première année d'Histoire et esthétique du cinéma doivent savoir identifier pour l'examen. Le film non inclu est Vie et Passion de Jésus Christ (Pathé, 1902-1907), le film est constituté d'une juxtaposition de tableaux filmés sur différentes années rend son implémentation impossible.

Des versions avec d'autres dataset sont tout à fait envisageable (listes thématiques, autres cours de cinéma, uniquement des séries, *etc*.)
Une version avec un dataset composé de séries et de films médicaux est accessible [ici](https://elentyr.itch.io/histoire-du-cinma-le-jeu-mystres-de-lunil-2023).  

## Libraires utilisées 
Le jeu a été développé avec la version 3000 de la librairie [Kaboom.js](https://kaboomjs.com/). Les données des films sont chargées via la librairie [d3.js](https://d3js.org/).

## Contexte de développement
Le code du jeu a été rédigé par Théo Rochat, étudiant de Master en Humanités Numériques et en Histoire et esthétique du cinéma. Ce projet a été développé dans le cadre du cours "Développement de jeu vidéo 2D" dispensé par Isaac Pante à l'Université de Lausanne.

## P.S.
Le jeu a été mis à jour pour correspondre aux films retenus pour le cours 2024-2025. 
Le jeu a également été exposé lors des Numerik Games 2023 à Yverdon, et fera l'objet d'une communication lors de la Summer School "Transposition ludique" organisé par le GameLab UNIL-EPFl à l'Université de Lausanne. 