#ensemble #entiers

# 1.1 Nombres entiers
## 1.1.1 Ensembles et notations
## 1.1.2 Addition et soustraction
**Addition :**
$\forall(a,b) \in \mathbb{N}^2, a+b \in \mathbb{N}$
$\forall(a,b) \in \mathbb{Z}^2, a+b \in \mathbb{Z}$

**Soustraction :**
$a, b \in \mathbb{Z}, a-b=a+(-b)$ où $-b$ est l'opposé de $b$

#définition Opposé $b'$ de $b \in \mathbb{N}$ est tq $b+b'=0$ , noté $-b$

#propriété $\forall b \in \mathbb{Z}, \exists!b',\in\mathbb{Z}, b+b'=0$

#démonstration
> Soit $b''$ tq $b+b''=0$,
> Comme $b'$ est opposé à $b$, on a $b+b'=0$
> $b'+(b+b')=b'+(b+b'') \iff (b'+b)+b' = (b'+b)+b'' \iff 0+b'=0+b''$  
> Donc $b'=b''$ $\blacksquare$   

=> L'**addition** des naturels et des relatifs est :
- **Commutative** : $a+b=b+a$
- **Associative** : $(a+b)+c=a+(b+c) = a+b+c$
- $0$ est **le neutre** de $+$ : $a+0=0+a=a$
- Tout relatif $b$ admet un unique opposé $-b$ tq $b+(-b)=-b+b=0$
- On définit la soustraction des relatifs : $a-b=a+(-b$

## 1.1.3 Multiplication et division

=> La **multiplication** des naturels et de relatifs est :
- **Commutative** : $ab=ba$
- **Associative** : $(ab)c=a(bc)=abc$
- $1$ est **élément neutre** : $a\times1=1\times a=a$
-  0 est **absorbant** : $0 \times a = a \times 0 = 0$
- #remarque  Les seuls entiers relatifs inversibles sont $1$ et $-1$.

#remarque La multiplication est distributive sur l'addition :
$$a(b+c) =ab+ac$$

#définition Soit $(a,b)\in \mathbb{Z}^2$, **a divise b** (noté $a|b$) $\iff \exists q \in \mathbb{Z}, b=aq$)
#remarque $0|0$

## 1.1.4 Les puissances
Pour $n \in \mathbb{N}$, on a : $$\{
\begin{aligned}
&x^0 = 1 \\
&x^{n+1} = x\times x^n
\end{aligned}$$
