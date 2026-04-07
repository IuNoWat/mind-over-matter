>**Version du Noyau :** 1.0
>**Date de Publication :** 10/09/2025
>**Auteur :** Lorenzo Jacques
>**Licence :** CC BY-NC-SA
>**But :**  Ce module sert à décrire des séquence de navigation sur un bateau à voile, en cherchant un équilibre entre un réalisme qui crée des enjeu de roleplay intéressants et des règles simples qui ne ralentissent pas trop le jeu.
>**En Bref :** La réussite ou l'échec d'un jet de navigation se fait sur un seul jet de dès du **Barreur** du bateau contre un Degré de Difficulté défini par la **Météo**. Ce jet vient être augmenté ou réduit par le score de l'ensemble de l'équipage qui est à la manœuvre. Selon la Météo et la réussite ou l'échec du Barreur, le navire progresseras plus ou moins sur sa trajectoire.
# Ce que contient ce module
- Deux compétences acquises :
	- Navigation : la capacité à conduire un navire et à calculer sa trajectoire dans l'espace et dans le temps
	- Marine : la capacité à manœuvrer les cordages et à suivre les ordres d'un capitaine
- Un système de résolution de déplacement jours par jours
- Un système de gestion de la Météo et du sens du Vent
- Des modèle de fiche personnage pour les bateaux
# Résoudre une action de navigation

## 1 - Définir le temps de trajet
Le temps de trajet est défini par un nombre de jour de voyages moyen à faire pour combler la distance entre le point de départ et le point d'arrivée des Personnages. C'est la Conteuse qui défini ce nombre de Jours Type, en se basant sur une carte ou sur ce qui lui semble pertinent.

Chaque jour de voyage, le jet de navigation des Joueuses déterminera si leur avancé est supérieure, égale ou inférieure à la distance d'un Jour Type. Au fur et à mesure des jours, la distance se réduit en fonction des réussites et des échecs des Personnages. 
## 2 - Définir la Météo
La Météo est tirée par la Conteuse, dans une table correspondant à la région dans laquelle se trouvent les personnages (une table générique est disponible plus bas). Cette table défini la force et le sens du vent, et par là le Degré de Difficulté du jet de navigation à effectuer, ainsi que la distance parcourue en cas de réussite ou d'échec.

Chaque jour, la Conteuse tire un D6. Si elle tombe sur 1, la Météo change, et elle doit donc relancer un jet dans la table de la région actuelle, pour choisir la nouvelle Météo de cette journée.

| **D20** |  **Vent**   | **Direction** | **Difficulté** | **Réussite** |         **Echec**          |
| :-----: | :---------: | :-----------: | :------------: | :----------: | :------------------------: |
|    1    | Calme Plat  |       -       |       -        |     _0_      |            _0_             |
|    2    |    Brise    |      Dos      |       20       |    _0.5_     |            _0_             |
|    3    | Vent Léger  |      Dos      |       6        |     _1_      |           _0.5_            |
|    4    | Vent Léger  |    Travers    |       12       |     _1_      |           _0.5_            |
|    5    | Vent Léger  |    Travers    |       12       |     _1_      |           _0.5_            |
|    6    | Vent Léger  |    Contre     |       18       |    _0.5_     |            _0_             |
|    7    | Vent Modéré |      Dos      |       8        |    _1.5_     |            _1_             |
|    8    | Vent Modéré |    Travers    |       14       |     _1_      |           _0.5_            |
|    9    | Vent Modéré |    Travers    |       14       |     _1_      |           _0.5_            |
|   10    | Vent Modéré |    Contre     |       20       |    _0.5_     |            _0_             |
|   11    |  Vent Fort  |      Dos      |       10       |    _1.5_     |            _1_             |
|   12    |  Vent Fort  |    Travers    |       16       |     _1_      |           _0.5_            |
|   13    |  Vent Fort  |    Travers    |       16       |     _1_      |           _0.5_            |
|   14    |  Vent Fort  |    Contre     |       22       |    _0.5_     |            _0_             |
|   15    | Grand Vent  |      Dos      |       12       |     _2_      |            _1_             |
|   16    | Grand Vent  |    Travers    |       18       |    _1.5_     |           _0.5_            |
|   17    | Grand Vent  |    Travers    |       18       |    _1.5_     |           _0.5_            |
|   18    | Grand Vent  |    Contre     |       24       |    _0.5_     |            _0_             |
|   19    |   Tempête   |      Dos      |       20       |    _0.5_     | _1 dans un sens aléatoire_ |
|   20    |   Tempête   |    Contre     |       20       |     _0_      |  _1 dans le sens inverse_  |
## 3 - Définir l'Equipage et son bonus total
Naviguer un bateau ne se fait (presque) jamais seul. Selon la taille du bateau que les Personnages commandent, ils auront besoin d'un équipage plus ou moins nombreux, et de plus ou moins de postes occupés.
### Postes Obligatoires
- Le **Barreur** est celui qui fait le jet global, en utilisant sa Force et sa compétence acquise de Navigation
- Les **Marins** manœuvrent les cordes et les voiles du navire, et ajoutent chacun le bonus de leur compétence acquise de Marine au jet du Barreur. (Il en faut entre 2 et plus de 50 selon la taille du navire)
- Le **Navigateur** calcule la position et la trajectoire du navire. Il ajoute le bonus de sa compétence de navigation au jet du Barreur.
- Le **Fiddler** motive l'équipage. Il ajoute le bonus de sa compétence de représentation.
### Postes facultatifs
- La **Vigie** peux faire faire un jet de Perception par jour, pour détecter les navires proches
- Le **Charpentier** peux faire des jets d'Artisanat pour réparer le navire et lui rendre des points de vie
- A partir de 6 Marins, le bon fonctionnement du navire nécessite un **Coq**. Il ajoute le bonus de sa compétence de Cuisine au jet du **Barreur**.
- A partir de 10 Marins, le bon fonctionnement du navire nécessite un **Contre-Maître**. Celui-ci ajoute son bonus de Présence au jet du Barreur

Si un Personnage tente d'assurer un poste sans avoir la compétence acquise associée, il donne un malus de -2 au jet du Barreur.
## 4 - Définir le jet du Barreur
C'est le **Barreur** (et non pas le **Capitaine**) qui fait le jet de navigation, sur sa Force et sa compétence de Navigation, contre le Degré de Difficulté de la Météo. Il reçoit également plusieurs bonus :
- Bonus des **Marins**
- Bonus du **Navigateur** (qui doit donc faire son jet de Navigation avant)
- Bonus ou malus du **Fiddler** (qui doit donc faire son jet de Représentation avant)
- Éventuel bonus ou malus du **Coq** (qui doit donc faire son jet de Cuisine avant)
- Éventuel bonus ou malus du Contre-Maître (qui doit donc faire son jet de Présence avant)
- Éventuel bonus de **Navire** (certains navires donnent des bonus sur certaines météo spécifiques (par exemple, un petit navire maniable profitera d'un bonus de +2 par Vent Léger)
## 5 - Interpréter le résultat
Selon la météo, la réussite ou l'échec au jet du **Barreur** donneront des résultats différents et réduirons plus ou moins la distance entre les Personnages et leur destination.