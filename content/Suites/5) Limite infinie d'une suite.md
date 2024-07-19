## Définition d'une suite divergente en +∞ 

Une suite tend vers +∞ lorsque tout intervalle de la forme $$[A; +∞[$$ contient tous les termes $$u_n$$ à partir d'un certain rang

Autrement dit pour tout $$A \in \mathbb{R}$$ il existe un rang $$n_0$$ tel que pour tout $$n \geq n_0, u_n \geq A$$

On note : $$\lim \limits _{n \to + \infty} u_n = + \infty$$

![[suite_A_n0.png|350]]
## Démontrer que la limite de Un = +∞

Soit $$n \in \mathbb{N} \space et A > 0 $$ on pose $$u_n = 4n² $$

On cherche à démontrer qu'il existe un rang $$n_0$$ à partir duquel $$u_n \geq A$$

$$u_n \geq A <=> 4n² \geq A <=> n² \geq \dfrac A 4 <=> n \geq \dfrac {\sqrt{A}}{2}$$

Cependant $$\dfrac {\sqrt{A}}{2}$$n'est généralement pas un entier naturel, on ne peut donc pas dire que $$n_0 = \dfrac {\sqrt{A}}{2}$$

On note alors $$n_0 = \lfloor \dfrac {\sqrt{A}}{2} \rfloor + 1$$

> [!note]
> $$\lfloor \dfrac {\sqrt{A}}{2} \rfloor $$ est la partie entière de $$\dfrac {\sqrt{A}}{2}$$. On rajoute + 1 car si $$\dfrac {\sqrt{A}}{2}$$ vallait par exemple 3,8, et bien sa partie entière serait 3, il manquerait donc 0,8


Dans ce cas, si  $$ n \geq n_0$$ on a $$u_n \geq A$$

Ainsi $$\lim \limits _{n \to + \infty} u_n = + \infty$$
## Démontrer que Un tend vers -∞

En cours d'écriture



