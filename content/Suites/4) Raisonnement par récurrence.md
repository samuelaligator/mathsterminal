Considérons une chaîne de dominos, faire tomber un domino entraîne son plus proche voisin dans sa chute et ainsi de suite.

Il y a deux conditions pour prouver que l'ensemble des dominos vont tomber.

Il faut prouver dans un premier temps, que **le premier domino soit pousser** et dans un second temps, il faut être certain que **la chute de n'importe quel domino entraîne le suivant**.

C'est le raisonnement par récurrence.

![[recurrence-dominos.png | 450]]
## Comment démontrer qu'une propriété est vraie ?

Pn désigne une propriété qui dépend d'un entier naturel n

### 1) Initialisation
Il faut vérifier que la propriété est vraie dès le départ. (par exemple à $$P_0$$)

### 2) Hérédité
On considère qu'a un certain rend $$n$$, $$P_n$$ soit vraie (c'est l'hypothèse de récurrence). Il faut démontrer que $$P_n+1$$ est vraie sachant que $$P_n$$ est vraie.

Il faut alors partir de la propriété au rang $$n$$ pour essayer de retrouver la propriété au rang $$n+1$$

## Exemple :
[[5) Inégalité de Bernoulli#Démonstration|Démonstration de l'inégalité de Bernoulli]]
 