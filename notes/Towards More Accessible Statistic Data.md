Afin de pouvoir comparer et mettre en relation des données statistiques issues de sources hétérogènes, l'équipe CEDAR à développé une solution pour rassembler différents jeux de données dans un format *standard* qui peut servir pour le fact-checking, ou la recherche en statistiques.

Ces bases de données contiennent des données *multidimensionnelles*, souvent dans des tableaux très grands et difficile à appréhender pour des chercheurs humains. 

Ainsi, la contribution du projet est double :
 - Une grande base de données issues de plusieurs sources, qui contient $238806$ tableaux multidimensionnels.
 - Une *méthodologie* pour modéliser, organiser et appréhender des grands corpus de texte.

> [!note]
> Le travail de l'équipe se limite a des données relativement texte-compatibles, et n'a pas tenté des faire de l'extraction d'images ou de PDFs.

### Bases de données statistiques

Tout d'abord, on commence par formaliser les données statistiques de façon à pouvoir intégrer des informations venant de n'importe quel dataset, indépendamment du format, de contraintes linguistiques, ...

On commence donc par des définitions :
 - On nomme *metric* quelque chose qui est mesuré plusieurs fois, et inclus dans un dataset
 - On nomme *dimension* une propriété d'un *metric*, comme le temps, l'endroit ou l'age, la taille et le genre.
 - On considère qu'une dimensions à plusieurs *granularities*, qui peuvent êtres organisées hiérarchiquement par ordre de précision, comme par exemple pour la position un continent est moins précis qu'un pays, qui est lui même moins précis qu'une ville.
 - Un *fact* est l'ensemble d'un *metric* plus un ensemble de *dimension*, un *data* (souvent un nombre) et parfois des commentaires.
 - Une *table* est un ensemble de fait organisés avec un titre.
 - Un *dataset* est un ensemble de *tables*.
 - Une *publication* est un ensemble de un ou plus dataset, associés à une URI et une description (optionnelle)
 - Une *datasource* est un provider d'une ou plus *publication*

### Organisation de dataset dans les sources

On développe un framework pour analyser et exploiter des sources de données en ligne qui peuvent être présentes sous différents formats.

On nomme *header cell* une cell qui contient le nom et/ou des valeurs d'une ou plusieurs dimensions, de granularité variable.



