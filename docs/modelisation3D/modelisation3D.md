ils existent plusieurs façon de modéliser en 3D

## les questions à se poser
 
### Quelle est la destination de mon modèle 3D ?

un modèle pour une impression3D, pour une fraiseuse numérique, un rendu réaliste, aucun de ces modèles n'aura les même caractéristique et ne seront pas conçu de la même façon.

### Quels matériaux ?
  
Chaque matériau à des propriètés physiques particulières, il faut un matériau compatible avec le modèle, avec son utilisation, sa disponibilité.


### Quelles machines ?

Caractéristiques et disponibilités de la machine ou du service.

### Passer tout le processus au filtre "utile, durable, accessible". 
  
  **Utile** : Est ce que vous ou l'humanité en a vraiment besoin

  **Durable** : changement climatique, finitude de la planète, Energie, matériaux ...ça vous dit quelques choses.

  **Accessible** : Vous travaillez à changer la planette et donc le magnimum de gens peuvent avoir accès, comprendre et réaliser votre projet. 


## Logiciels de modélisation

je vous met ce film de Gleb Alexandrov (adepte du logiciel blender) qui montre bien l'incroyable diversité d'outils et les styles qui en découlent 

<iframe width="560" height="315" src="https://www.youtube.com/embed/DeHasEMCzcc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Paramétrique et procédural.
il s'agit de définir chaque étapes de conception de l'objet par un algoritme paramétré.

Chaque étape se succède et peut être édité à posteriori.
*ainsi si à l'etape 12 j'ai réalisé des trous pour recevoir des vis M3 et qu'a l'étape 20 je m'apperçois que ce serait mieux avec du M4
je peux éditer la dimension à l'étape 12 et toute les étapes jusqu'à l'étape 20 seront recalculé.*

Les limites : la modélisation se fait a travers le carcan des outils du logiciel (les algoritmes disponibles), généralement en relation avec les outils du monde industiel. il est difficile d'avoir des formes organiques ou des formes qui ne sont pas issues de primitive "mathématique"

### Maillage

Le modèle est représenté par des points dans l'espace relié entre eux (mesh).
La génération des points peut être algoritmique mais souvent des étapes critiques font perdre le caractère éditable de chaque étape.

### Modélisation génerative

<iframe width="560" height="315" src="https://www.youtube.com/embed/P99k3TUbkuU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Choix du logiciel 

Malgrès ces deux grandes familles les logiciels ont évolué et proposent de plus en plus d'outils qui étendent leurs champs des possibles il est donc pas si aisé de catalogué un logiciel.
il faut en comprendre la philosophie, la mise en oeuvre un peu comme on choisi un vélo.
La taille du cadre me convient elle, la selle est elle confortable, les vitesses sont elles adaptées à mes parcours quotidient et le plus important est ce que les poignées sont confortable ;-).

#### Scanner

Pour obtenir un modèle il est possible aussi pour un modèle existant de le scanner c'est a dire de relever point par point la position de l'objet dans l'espace et transférer ce "nuage de points" dans un logiciel adapté pour le rendre "maillage" mo, modéle 3D

#### Scanner laser

#todo

#### Scanner lumiere 

#todo

## Photogrammétrie

La photogrammétrie prend une grande quantité d'image d'un objet pour en déterminer son volume. Sa précision n'est pas celle des scanners proféssionnels laser mais bien réalisé elle ne dépasse pas 0.2mm ce qui la plupart du temps est bien suffisant.
