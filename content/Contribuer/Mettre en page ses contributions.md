Mind Over Matter est conçu pour être aussi léger, accessible et modulaire que possible. Il utilise pour cela le format [Markdown](https://fr.wikipedia.org/wiki/Markdown), qui offre quelques options de mise en page.

En plus des options de base du langage, Mind Over Matter a été conçu grâce à l'éditeur [[Utiliser Obsidian|Obsidian]], qui ajoute quelques fonctionnalités pratiques.

Retrouvez ici l'ensemble des éléments de mise en page standards que vous pourrez retrouver sur ce site.

# 🔢 Hiérarchiser sa pensée
N'hésitez pas à utiliser au maximum les titres hiérarchisés pour que vos lecteurs puissent s'orienter dans votre réflexion. Ces titres seront aussi visibles et cliquables dans la partie inférieure droite du site web.
# Titre 1
## Titre 2
### Titre 3
#### Titre 4
##### Titre 5

Les listes et listes numérotées permettent de souligner respectivement les choix multiples et les étapes d'un processus :
- Option 1
- Option 2
- Option 3
1. Première étape
2. Deuxième étape
3. Troisième étape

# 🕸 Penser en réseau

La fonctionnalité la plus utile d'Obsidian est sans contexte le wikilien : [[Utiliser Obsidian]].
Il est également possible d'intégrer une page à l'intérieur d'une autre :
![[Joueuse]]

# 💥 Souligner les éléments importants

Au sein d'un même paragraphe, nous vous recommandons d'utiliser au maximum les outils de mise en valeur de texte pour fluidifier la compréhensions de vos écrits.  En gras, **les éléments à retenir**, en italique, *les suggestions ou les conseils facultatifs*.

Pour mettre en évidence un paragraphe, vous pouvez utiliser la citation et les blocs :

> Une citation

>[!tip]
>Et un bloc

# 📑 Réserver les tableaux aux chiffres

Bien que disponible, nous vous invitons à limiter l'usage des tableaux aux valeurs numérique propres au Jeu.

| Colonne 1                |         Colonne 2         |                Colonne 3 |
| :----------------------- | :-----------------------: | -----------------------: |
| Colonne alignée à gauche | Colonne alignée au centre | Colonne alignée à droite |

|Adresse|Charisme|Force|Intelligence|Instinct|
|:-:|:-:|:-:|:-:|:-:|
|10|10|10|10|10|

# 🔘 Créer un boutton
## Bouton en pleine page
```
<a href="" class="grid-item">
<div class="icon"></div>
<div class="title">Mind Over Matter</div>
<div class="description">Retourner à l'accueil</div>
</a>
```
### Exemple
<a href="" class="grid-item">
<div class="icon"></div>
<div class="title">Mind Over Matter</div>
<div class="description">Retourner à l'accueil</div>
</a>

## Grille de Bouton
```
<div class="grid-container">

<a href="Noyaux" class="grid-item">
<div class="icon">📖</div>
<div class="title">Bouton 1</div>
<div class="description">Tous les Noyaux disponibles</div>
</a>

<a href="Noyaux" class="grid-item">
<div class="icon">📖</div>
<div class="title">Bouton 2</div>
<div class="description">Tous les Noyaux disponibles</div>
</a>

<a href="Noyaux" class="grid-item">
<div class="icon">📖</div>
<div class="title">Bouton 3</div>
<div class="description">Tous les Noyaux disponibles</div>
</a>

</div>
```
### Exemple
<div class="grid-container">

<a href="Noyaux" class="grid-item">
<div class="icon">📖</div>
<div class="title">Bouton 1</div>
<div class="description">Tous les Noyaux disponibles</div>
</a>

<a href="Noyaux" class="grid-item">
<div class="icon">📖</div>
<div class="title">Bouton 2</div>
<div class="description">Tous les Noyaux disponibles</div>
</a>

<a href="Noyaux" class="grid-item">
<div class="icon">📖</div>
<div class="title">Bouton 3</div>
<div class="description">Tous les Noyaux disponibles</div>
</a>

</div>