# 1.3 Nombres réels et inégalités
## 1.3.1 Nombres réels

#définition Intervalle de $\mathbb{R}$ : 
	 I est un intervalle **convexe** de $\mathbb{R}$ ssi $I \subset \mathbb{R}$ et $\forall (x,y)\in I^2, \forall z \in \mathbb{R}, x \leq z \leq z \implies z\in I$	
	**Exemples :**
	- $\emptyset$ 
	- $\mathbb{R}$
	- $\mathbb{R}_+ = \mathbb{R}^+ = R_{\geq 0} = [0;+\infty[ = \{x\in\mathbb{R} | x\geq0\}$ 
	- $\mathbb{R}_+^* = \mathbb{R}_+ \backslash \{0\}$  
	**Contre exemples :**
	- $I=\{0;1\}$ car pour $z=\frac{1}{2}$, $0 \leq z \leq 1$ et $z \not\in I$
	- $I = \mathbb{N}$
	- $I = \mathbb{Q}$ car $\forall (q,q') in \mathbb{Q}^2, \exists z \in\mathbb{R}\backslash\mathbb{Q}, q<z<q'$
#définition Un ensemble $D$ des réels est dense dans $\mathbb{R}$ ssi $\forall x < y \in \mathbb{R}, \exists d \in D, x < d < y$

## 1.3.2 Inégalités et opérations algébriques
$a \leq b \implies f(a) \leq f(b)$ si $f$ est une fonction croissante sur $[a;b]$
$a \leq b \implies f(a) \geq f(b)$ si $f$ est décroissante sur $[a;b]$

$a < b \implies f(a) < f(b)$ si $f$ est une fonction strictement croissante sur $[a;b]$
$a > b \implies f(a) < f(b)$ si $f$ est strictement décroissante sur $[a;b]$

> #remarque Vraie #définition de la croissance : Pour $I\subset\mathbb{R},\forall(x,y)\in I^2, x \leq y \implies f(x) \leq f(y)$

```functionplot
---
title: Inverse
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
y(x)=1/x
```
⚠️ On a $x \leq y \implies \frac{1}{x}\geq\frac{1}{y}$ quand $x$ et $y$ sont de même signe

*Exercice pour la maison : Montrer que la racine carré est unique ($\sqrt{a}$ est le nombre dans $\mathbb{R}_+$ tq $r^2=a$)

#définition **Valeur absolue :** Soit $x \in \mathbb{R}$, $|x| = \left\{ \begin{aligned}x &\text{ si } x\geq0 \\ -x &\text{ si } x\leq0 \end{aligned}\right.$.
#propriété $|x|=\sqrt{x^2}$ 
#propriété $\forall x \in \mathbb{R}, |x| \geq 0$
	#démonstration 
	Si $x\geq0$, alors $|x|=x\geq0$
	Sinon $|x| = -x$, or $-x\geq0$ donc $|x|\geq0$
	Comme $x$ est soit positif, soit négatif, alors $\forall x\in\mathbb{R},|x|\geq0$ 	
	$\blacksquare$
	-
#propriété ==/!\\ $|x| \leq M \iff -M \leq x \leq M$ /!\\== 
	 #démonstration <span style="border: solid 1px black; border-radius: 99px; padding: 2px; aspect-ratio: 1/1;">=></span>
	 Supposons $|x|\leq M$
	 Comme $M \geq |x| \geq0$, on doit avoir $M\geq0$
	 Si $x\geq0$, alors $|x|=x$ et $x \leq M$, et comme $x\geq0,x\geq-M$ 
	 Sinon $x\leq0$ et $|x|=-x$, donc $-x \leq -M \iff x \leq -M$, et comme $x\leq0$ et $M\geq0$
	 Dans tous les cas, on a bien $-M < x < M$
	 > Note : l'équivalence est perdue avec le raisonnement par cas
	 #démonstration <span style="border: solid 1px black; border-radius: 99px; padding: 2px; aspect-ratio: 1/1;">&lt=</span>
	Supposons $-M \leq X \leq M$
	

#propriété $a,b,c,d\in\mathbb{R}_+, a\leq b\land c\leq d \implies ac\leq bd$ 
	#démonstration 
	En effet, soit $a, b, c, d\in\mathbb{R}_+$.
	Supposons $a\leq b$ et $c\leq d$.
	Comme $c\geq0$, de $a\leq b$ , on déduit $ac \leq bc$
	Et comme $b \geq 0$, de $c \leq d$, on déduit $bc \leq bd$
	Donc, par transitivité, on a : $ac \leq bc \leq bd \iff ac \leq bd$
	$\blacksquare$
	---
