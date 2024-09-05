## Définition

On dit que la suite $$u_n$$ admet pour limite L si tout intervalle ouvert contenant L contient tous les termes de la suite à partir d'un certain rang

on note $$\lim \limits _{n \to + \infty} u_n = L$$

Une telle suite est dite convergente : elle admet une limite finie.

>[!remarque]
>Une suite qui n'est pas convergente est dite **divergente** (suite qui n'admet pas de limite finie)
>
>  Ex: [[7) Les suites divergentes en l'infini|Les suites divergentes en l'infini]]


![[suite_convergente.png]]

## Théorème de la limite monotone

- Si une suite croissante est majorée alors elle est convergente.
- Si une suite décroissante est minorée alors elle est convergente.

## Exemple : démontrer qu'une suite est convergente

Soit $$u_0 = 0$$ et $$u_{n+1} = \sqrt{3u_n + 4}$$
### **1) Démontrer que** $$u_n$$est majorée par 4.

Nous allons démontrer par un raisonnement par récurrence que $$u_n$$est majorée par 4.

**Étape 1 : Initialisation.** 

On vérifie que la propriété est vraie au premier rang, ici $$u_0$$.

$$u_0 \leq 4$$

La propriété est donc initialisée.

**Étape 2 : Hérédité.** 

On pose l'hypothèse que $$u_n \leq 4 $$

On part de cette inégalité pour retrouver $$u_{n+1}$$

$$\leftrightarrow 3u_n \leq 12 $$

$$\leftrightarrow 3u_n +4 \leq 16 $$

$$\leftrightarrow \sqrt {3u_n +4} \leq 4$$

$$ \leftrightarrow u_{n+1} \leq 4$$


Par récurrence nous venons donc de démontrer que la suite est majorée par 4.

### 2) Démontrer que $$u_n$$ est croissante.

Nous allons démontrer par un raisonnement par récurrence que $$u_n$$ est croissante.

**Étape 1 : Initialisation.**

On calcule $$u_0 \space et \space u_1$$ pour vérifier que la suite est croissante aux premiers rangs.

$$u_0 = 0$$


$$u_1 = 2$$


$$u_0 \leq u_1$$


La propriété est donc initialisée.

**Étape 2 : Hérédité.**

On pose l'hypothèse qu'à un rang  $$n$$ la suite est croissante 

$$u_n \leq u_{n+1}$$

On part de cette inégalité pour retrouver  $$u_{n+1} \leq u_{n+2}$$


$$\leftrightarrow 3u_n \leq 3u_{n+1}$$


$$\leftrightarrow \sqrt {3u_n +4} \leq \sqrt {3u_{n+1} +4} $$

$$ \leftrightarrow u_{n+1} \leq u_{n+2}$$

Nous avons donc démontré par récurrence que la suite $$u_n$$ est croissante

### 3) Conclusion
La suite $$u_n$$ converge donc car elle est croissante et majorée
