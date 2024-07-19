
Pour tout réel a > 0, pour tout entier naturel n

On a : $$\boldsymbol{(1+a)^n \geq 1 +na}$$

## Démonstration

[[3) Raisonnement par récurrence|Pour comprendre comment fonctionne un raisonnement par récurrence]]


### Initialisation
On vérifie si la propriété est vraie pour n = 0 


$$ (1+a)^0 = 1\space et \space 1 + 0 \times a = 1 $$


$$Or \space 1 \geq 1 \space donc \space (1+a)^0 \geq 1 + 0 \times a$$

La propriété est donc initialisée.

### Hérédité

<p><strong>Hypothèse de récurrence</strong> :<br>
On suppose que la propriété est vraie au rang  n.</p>

Cela signifie donc que 

$$(1+a)^n\geq \textcolor{red}{1 + na}$$

On veut démontrer que la propriété est vraie au rang n+1

$$(1 + a)^{n + 1} \geq \textcolor{green}{ 1 + (n + 1)a}$$

<p>On part d'un côté pour essayer de rejoindre l'autre côté de l'inégalité<br>
On descend d'un rang pour pouvoir utiliser l'hypothèse de récurrence</p>

$$(1 + a)^{n+1} = (1+a)^n(1+a)^1$$

On utilise l'hypothèse de récurrence

$$ (1+a)^n(1+a) \geq \textcolor{red}{(1 + na)}(1 + a)$$

On développe

$$ (1 + a)^{n+1} \geq 1 + a + na + na²$$

On factorise

$$ (1 + a)^{n+1} \geq 1 + (n + 1)a + na²$$

Comme $$ na²$$ est un nombre positif (n est un entier naturel donc positif & a² positif), on peux le faire disparaître de l'inégalité. On a donc retrouvé $$\textcolor{green}{ 1 + (n + 1)a}$$

$$ (1 + a)^{n+1} \geq \textcolor{green}{ 1 + (n + 1)a}$$

### Conclusion

La propriété est vraie pour n = 0 et elle est héréditaire à partir de ce rang, elle est donc vraie pour tout entier naturel n.
