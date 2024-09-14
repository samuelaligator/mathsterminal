Un graphe est constitué de _sommets_ (ou nœuds) reliés par des _arêtes_ (ou liens). Si les arêtes sont fléchées, on parle de _graphe orienté_ sinon on parle de _graphe non-orienté_. Dans un graphe orienté, on appelle _parents_ d'un nœud, les nœuds qui pointent vers lui. On appelle _fils_ d'un nœud, les nœuds vers lesquels il pointe.

Un graphe peut représenter un réseau social, des liens d'amitié, un réseau routier.

Ce graphes est orienté, il a 6 sommets et 8 arêtes

![[graphe_oriente.svg ]]



On utilisera parfois des graphes pondérés pour représenter par exemple des distances sur une carte. Dans un tel graphe, les arêtes sont associées à un poids :

![[graphe_pondere.svg]]
## Propriétés

Les propriété les plus communes pour parler d'un graphe sont les suivantes :

- une _chaîne_ (ou _chemin_) est une suite d'arêtes consécutives ;
- la longueur d'un chaîne est le nombre d'arêtes qui la compose ;
- la _distance_ entre deux sommets est la longueur de la chaîne la plus courte entre ces deux sommets ;
- un _cycle_ est une chaîne fermée. C'est à dire qui commence et termine par le même sommet.


La distance entre A et D est 
![[graphe_non_oriente.svg]]

## Implémentations

On parle d'implémentation lorsqu'il s'agit de « représenter » un graphe dans un système informatique. Même si nous ne verrons pas directement comment on implémente un graphe en Python nous allons parler des deux principales implémentations d'un graphe.

![[matrice.svg]]

Nous avons ci-dessus une matrice à 3 lignes et 4 colonnes. En mathématiques on utilise les matrices pour effectuer des calculs, nous les utiliserons ici simplement comme des tableaux à deux dimensions.

Une matrice d'adjacence est une matrice carrée (même nombre de lignes que de colonnes) où chaque ligne et chaque colonne représentent un sommet. Pour un graphe non-orienté on mettra un « 1 » sur la case [i][j] s'il y a une arête entre le sommet i et le sommet j, et un « 0 » sinon. Pour un graphe orienté on mettra un « 1 » sur la case [i][j] s'il y a une arête du sommet i vers le sommet j, et un « 0 » sinon. Pour un graphe pondéré on mettra sur la case [i][j] le poids du lien entre le sommet i et le sommet j.