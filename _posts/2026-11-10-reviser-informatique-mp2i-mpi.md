---
date: 2026-11-10 17:00:00
layout: post
title: "Prépa MP2I/MPI : une méthode concrète pour progresser en programmation"
subtitle: Passer des annales à des programmes que l'on sait expliquer, tester et corriger
image: img/ecrits.jpeg
category: outils
tags:
  - MP2I
  - MPI
  - Informatique
  - Algorithmique
  - Programmation
  - Concours
  - Révisions
  - Prépa Shelter
  - Prépa
paginate: true
---

En prépa, l'informatique se travaille mal quand elle devient une liste de chapitres à « revoir ». Lire un corrigé de file, de graphe ou de programmation dynamique donne vite l'impression d'avoir compris. Puis il faut écrire une fonction, justifier sa complexité ou repérer un cas limite, et le blanc revient.

L'objectif n'est pas de faire du code pour faire du code. Il faut apprendre à passer d'un énoncé à une représentation, puis à un programme dont chaque choix se défend. C'est ce qui sert dans les sujets, à l'oral, et plus tard dans une école d'informatique.

## Commencer par le bon périmètre

Le programme officiel distingue bien les voies [MP2I et MPI](https://www.education.gouv.fr/bo/21/Special1/ESRS2035777A.htm). Avant d'ouvrir une ressource, note sur une feuille le chapitre du moment et ce que l'on attend de toi : manipuler une structure, prouver un invariant, analyser un coût, ou produire une implémentation.

Ne mélange pas trois entraînements différents :

1. apprendre le cours et savoir refaire une preuve ;
2. résoudre un exercice de concours dans son format complet ;
3. écrire du code jusqu'à ce qu'il se comporte correctement sur des entrées pénibles.

Une annale peut servir aux trois, mais pas dans la même séance. La première lecture peut viser la méthode. Une autre séance peut isoler une fonction. Le sujet entier vient après, quand les briques arrêtent de te ralentir.

Les [sujets de concours déjà rassemblés sur Prépa Shelter](/sujets-concours/) donnent une bonne matière pour choisir un thème. Pour les sujets et les rapports récents de CentraleSupélec, la [page officielle du concours](https://www.concours-centrale-supelec.fr/sujets-rapports) est la bonne source. Les rapports sont utiles : ils disent ce qui a réellement séparé les copies, au-delà de l'intitulé d'un chapitre.

## Faire une séance courte qui produit quelque chose

Une séance de 45 à 75 minutes suffit si elle laisse une trace précise. Voici un format qui évite de passer une soirée entière à relire un corrigé.

1. Choisis une sous-question d'annale ou un exercice, pas un grand thème. « Écrire l'insertion dans un tas » est exploitable. « Revoir les graphes » ne l'est pas.
2. Écris avant de coder ce que représentent tes variables et ce que la fonction promet de renvoyer. Si tu ne peux pas le dire en deux phrases, le code partira au hasard.
3. Liste trois entrées avant la première ligne : le cas minimal, un cas normal, un cas qui casse une hypothèse. Pour une recherche, pense à la structure vide, à l'élément absent et au dernier indice. Pour une récursion, pense au cas de base avant l'appel récursif.
4. Écris la fonction sans regarder le corrigé pendant quelques minutes. Si tu bloques, reviens à l'invariant ou dessine un exemple à la main, plutôt que de chercher tout de suite une solution complète.
5. Termine par trois lignes : ce qui t'a bloqué, le test qui l'a révélé, et la complexité obtenue. C'est ce document qui rend la prochaine révision rapide.

Le chrono sert à garder le rythme, pas à imiter l'épreuve à chaque fois. En début d'apprentissage, comprendre pourquoi le tableau a une case de trop vaut plus qu'une solution rendue cinq minutes plus tôt.

## Transformer une annale en terrain d'entraînement

Un énoncé de concours contient souvent plusieurs couches. Il demande par exemple de choisir une structure, de prouver une propriété, d'implémenter une opération, puis de mesurer son coût. Essayer de tout programmer d'un coup cache la première erreur sous les suivantes.

Prends plutôt une question qui manipule une structure et fabrique un petit banc d'essai. Si tu travailles une file, vérifie une file vide, une insertion suivie d'une sortie, puis une suite d'opérations. Si tu travailles un graphe, prépare un sommet isolé, une arête répétée et un chemin qui n'existe pas. Le sujet ne donne pas toujours ces cas, mais ils montrent vite si tu as compris les conventions de représentation.

Après seulement, compare avec le corrigé. Ne compare pas uniquement les lignes de code. Cherche :

- l'invariant que le corrigé maintient ;
- le cas limite qu'il traite avant les autres ;
- le coût annoncé et l'opération qui le justifie ;
- la différence entre ton modèle mental et la structure réellement utilisée.

Cette comparaison est plus rentable que recopier une correction parfaite. Elle te donne une erreur nommable, donc corrigeable.

## Garder un espace pour la pratique de code

Le code de prépa est souvent un moyen de raisonner. Pourtant, un peu de pratique hors annale aide beaucoup à enlever les frottements : indices décalés, chaîne non terminée, condition d'arrêt oubliée, allocation non libérée, valeur de retour ignorée.

Si tu veux travailler le C avec des exercices corrigés automatiquement, [Grademe](https://grademe.io/app/learn/c?utm_source=prepashelter&utm_medium=referral&utm_campaign=mp2i_mpi_programming) propose un parcours dans le navigateur. C'est utile pour isoler une difficulté technique avant de la retrouver dans un sujet plus long : chaînes, tableaux, pointeurs, récursion, structures de données. Ce n'est ni une annale CPGE ni un substitut au cours. C'est un endroit pour répéter une mécanique jusqu'à ce qu'elle ne prenne plus toute ton attention.

Le principe vaut aussi dans le langage de ton cours. Le support change, mais la discipline reste la même : comprendre le contrat d'une fonction, construire un exemple, vérifier les cas limites, puis expliquer ce que fait l'algorithme.

## Réviser sans abandonner le reste de la semaine

L'informatique progresse mieux avec deux petits rendez-vous qu'avec une grosse session impossible à replacer. Une séance peut servir à écrire et tester une fonction. L'autre à reprendre une question d'annale et expliquer la solution sans regarder tes notes.

Quand les écrits approchent, garde les annales dans leur format réel. Quand tu prépares un oral, entraîne-toi à présenter l'état d'une structure et l'idée d'un algorithme à voix haute. Un programme qui passe tes tests mais que tu ne peux pas expliquer reste fragile.

Le bon indicateur n'est pas le nombre d'exercices cochés. C'est ta capacité à retrouver, quelques jours plus tard, pourquoi une boucle s'arrête, ce que contient une structure à chaque étape, et quel test ferait tomber ton propre programme.

Pour aller plus loin, utilise les annales de ce site pour choisir une question précise, le programme officiel pour vérifier le périmètre, et une pratique régulière pour ne pas laisser la programmation devenir un chapitre que l'on « connaît » sans pouvoir l'écrire.
