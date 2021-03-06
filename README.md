# Chaîne de Markov: Réservoir

Dans ce travail, on va utiliser quelques concepts vu sur les Chaînes de Markov, plus précisement:

- Comment démontrer que Z_n, n>=0 est une Chaîne de Markov
- Espace d'états
- Fonction de transition
- Tracer trajectoires (simulation) 
- Calcul analytique
- Estimer la moyenne et la variance
- Loi stationnaire

Dans ce repository, vous pouvez trouver trois  fichiers:

- Ennonce_Réservoir (pdf fichier): Le problème à résoudre
- Réservoir.Rmd (Markdown fichier): Il s'agit d'un notebook où se trouve implementé notre solution aux questions du énoncé. Tout le code se trouve en langage de programmation R.
- Markov chain_Reservoir (pdf fichier): Rapport du projet final inspiré sur le fichier Markdown

En complément à l’énoncé, on travaille sur la loi suivant pour l’aliméntation du réservoir :

p(0)=0.1 |
p(1)=0.6 |
p(2)=0.1 |
p(i)=0.05,  i=3,4,5,6.

## Getting Started

Ce projet a utilisé le langage de programmation R. Il est donc nécessaire d'utiliser les libraries: markovchain, ggplot2 et reshape2 

**Collaborateurs:**
- Luis González
- Estia Maliqari
