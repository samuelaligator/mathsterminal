
Pour tout réel a > 0, pour tout entier naturel n

On a : $$\boldsymbol{(1+a)^n \geq 1 +na}$$

## Démonstration

[[4) Raisonnement par récurrence|Lien pour comprendre comment fonctionne un raisonnement par récurrence]]


### Initialisation
On vérifie si la propriété est vraie au premier rang, ici pour n = 0 


$$ (1+a)^0 = 1\space et \space 1 + 0 \times a = 1 $$


$$Or \space 1 \geq 1 \space donc \space (1+a)^0 \geq 1 + 0 \times a$$

La propriété est donc initialisée.

### Hérédité

<p><strong>Hypothèse de récurrence</strong> :<br>
On suppose que la propriété est vraie au rang  n.</p>

Cela signifie donc que 

$$\textcolor{red}{(1+a)^n}\geq \textcolor{red}{1 + na}$$

On veut démontrer que la propriété est vraie au rang n+1

$$\textcolor{green}{(1 + a)^{n + 1} \geq  1 + (n + 1)a}$$


On descend d'un rang pour pouvoir utiliser l'hypothèse de récurrence

$$(1 + a)^{n+1} = (1+a)^n(1+a)^1$$

On ajoute (1 + a) à l'hypothèse de récurrence pour retrouver la propriété au rang n+1

$$ \textcolor{red}{(1+a)^n}(1+a) \geq \textcolor{red}{(1 + na)}(1 + a)$$

On développe

$$ (1 + a)^{n+1} \geq 1 + a + na + na²$$

On factorise

$$ (1 + a)^{n+1} \geq 1 + (n + 1)a + na²$$

Comme $$ na²$$ est un nombre positif (n est un entier naturel donc positif & a² positif), on peux le faire disparaître de l'inégalité. On a donc retrouvé la propriété au rang n+1

$$\textcolor{green}{ (1 + a)^{n+1} \geq  1 + (n + 1)a}$$

### Conclusion

La propriété est vraie pour n = 0 et elle est héréditaire à partir de ce rang, elle est donc vraie pour tout entier naturel n.

