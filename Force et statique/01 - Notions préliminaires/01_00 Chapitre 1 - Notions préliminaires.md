Définitions
---

#définition **Mécanique :** étude du mouvement des objets et de l'absence de mouvement
#définition **Cinématique :** étude descriptive (trajectoire, vitesse, accélération)
#définition **Dynamique :** étude du lien entre les forces et le mouvement / l'équilibre
#définition **Etats de la matière :** 
- __solide :__
	Distance faible entre les molécules : $\mathring{A} \sim 10^{-10}m$
	forme propre, quasi incompressible 
- __liquide :__
	Distance moyenne entre les molécules
	Pas de forme propre, quasi incompressible
- __gazeux :__
	Distance élevée entre les molécules
	Pas de forme propre, compressible
**Exemple :** $1L$ d'air $\approx$ $3\cdot10^{22}$ molécules $\rightsquigarrow$ $30 \mathring{A}$ entre chaque molécule

#définition **Mécanique du point :** mécanique où l'on résume un objet à un point matériel qui a une masse, de la charge, etc.
#définition **Référentiel :** $(0, \vec{e_x}, \vec{e_y}, \vec{e_z})$

![[Assets/IMG_20240912_151917.jpg]]

Dans la mécanique newtonienne, on ignore la relativité du temps et on suppose que le temps est absolu. Cela marche bien tant qu'on s'éloigne des grandes vitesses et des petites distances

#formule **PFD :** *Principes fondamental de la dynamique* $\sum{\vec{F}} = m\vec{a}$
#formule **PAR :** *Principe des axiomes réciproques* $\vec{F}_{A\rightarrow B} + \vec{F}_{B \rightarrow A} = \vec{0}$

PDF et PAR sont représentés par les 3 lois de Newton :
1. **Principe d'inertie :** Un point matériel isolé est en mouvement de translation rectiligne uniforme
2. **PFD**
3. **PAR**

Cadre mathématique : Les vecteurs
---

#définition Un **vecteur** est un segment orienté qui joint deux points de l'espace

![[IMG_20240912_154053.jpg]]

**Vecteur lié :** Est un vecteur qui est lié à un point donné 
	*Exemple :* $\vec{OA}$
**Vecteur libre :** $\neg$Vecteur libre
	*Exemple :* vecteur champ électrique $\vec{E}$

#définition **Scalaire :** nombre défini avec l'espace $\mathbb{R}$ *(espace scalaire)*
	*Exemple :* Température
#définition **Vecteur :** quantité définie avec $\mathbb{R}^3$ *(espace vectoriel)*. vecteur $\equiv$ 3 nombres
	*Exemple :* Vent

> $\xcancel{\vec{a} = 0}$
> /!\\ Aux dimensions !!!

L'espace $\mathbb{R}^3$ : 3 réels
$\rightarrow$ Base unitaire orthonormée directe
**unitaire :** vecteurs unitaires de longueur 1
**orthonormé :** vecteurs orthogonaux deux à deux
**directe :** les fameux trois doigts (°c_°)

$\vec{a} = \begin{pmatrix}a_x \\ a_y \\ a_z \end{pmatrix} = a_x\vec{e_x} + a_y\vec{e_y} + a_z\vec{e_z}$

## Propriétés :
#propriété **Représentation :** On représente un vecteur par un segment orienté *(une flèche ptdrr)*
#propriété **Somme de vecteurs :** $\vec{a}\begin{pmatrix}a_x\\a_y\\a_z\end{pmatrix} + \vec{b}\begin{pmatrix}b_x\\b_y\\b_z\end{pmatrix} = \vec{a}+\vec{b}\begin{pmatrix}a_x+b_x\\a_y+b_y\\a_z+b_z\end{pmatrix}$ 
#propriété **Multiplication par un scalaire :** $k\cdot\vec{a}\begin{pmatrix}a_x\\a_y\\a_z\end{pmatrix} = k\vec{a}\begin{pmatrix}k\cdot a_x\\k\cdot a_y\\k\cdot a_z\end{pmatrix}$
#propriété **Produit scalaire de deux vecteurs :** $\vec{a} \cdot \vec{b} = a\times b\times \cos{(\vec{a};\vec{b})} = a_xb_x+a_yb_y+a_zb_z$

### Exercice :
$\vec{a} = \begin{pmatrix}\sqrt{10}\\-3\\5\end{pmatrix}$
$\vec{b} = \begin{pmatrix}6\\2\sqrt{10}\\2\end{pmatrix}$
$\vec{a} \cdot \vec{b} = 10$

#propriété $||\vec{a}|| = a = \sqrt{\vec{a} \cdot \vec{a}}$
#propriété La norme d'un vecteur unitaire est de 1
#propriété Si deux vecteurs sont orthogonaux, alors leur produit scalaire est nul. La réciproque n'est pas vraie
#propriété Le produit scalaire est commutatif : $\vec{a}\cdot\vec{b}=\vec{b}\cdot\vec{a}$
#propriété Le produit scalaire se distribue : 
	$\vec{a}(\vec{b}+\vec{c}) = \vec{a}\cdot\vec{b}+\vec{a}\cdot\vec{c}$  
	$\vec{a}(\lambda\vec{b}) = \lambda(\vec{a}\cdot\vec{b})$

### Exemples 
1. Le travail (cas d'une force constante) :
$$W_{A\rightarrow B}(\vec{F}) = \vec{F} \cdot \vec{AB}$$
2. $E_c = \frac{1}{2}mv^2=\frac{1}{2}m\vec{v}\cdot\vec{v}$

#propriété **Produit scalaire et angle :** $\vec{a}\cdot\vec{b} = a\times b\times\cos(\widehat{\vec{a};\vec{b}})$

# Produit vectoriel de deux vecteurs :
#définition On appelle **produit vectoriel** de deux vecteurs $\vec{a}$ et $\vec{b}$ le vecteur dont les composantes sont : $$\vec{a}\begin{pmatrix}a_x\\a_y\\a_z\end{pmatrix} + \vec{b}\begin{pmatrix}b_x\\b_y\\b_z\end{pmatrix} = \begin{pmatrix}a_yb_z-a_zb_y \\ a_zb_x-a_xb_z\\a_xb_y-a_yb_x\end{pmatrix}$$
## Propriétés :
#propriété Le produit vectoriel n'est **pas** commutatif ! $\vec{a} \land \vec{b} = -\vec{b} \land \vec{a}$
#propriété Distributivité : $\vec{a} \land (\vec{b}+\vec{c}) = \vec{a}\land\vec{b}+\vec{a}\land\vec{c}$
#propriété $\vec{a}\land\vec{b}=\vec{0}$ si $\left\{\begin{aligned}\vec{a}//\vec{b} \\\vec{a}=0 \\\vec{b}=0\end{aligned}\right.$
#propriété Produit vectoriel et angle : $\vec{a} \land \vec{b} = a \times b \times |sin(\vec{a};\vec{b})|$

## Exemple d'utilisation :
1. Si on a une force $\vec{F}$ appliquée sur un point $M$ d'un solide, on parle de $\vec{\mathcal{M}}$ (moment) de la force par rapport à une origine $O$ tq $\vec{\mathcal{M}} = \vec{OM} \land \vec{F}$.
2. Forces de Lorentz :
	![[IMG_20240918_153535.jpg]]
	$\vec{F_\mathcal{L}} = q(\vec{E}+\vec{v}\land\vec{B})$

# Rappels de trigonométrie :
![[th.png]]

| $\theta$     | $0$ | $\frac{\pi}{6}$      | $\frac{\pi}{4}$      | $\frac{\pi}{3}$      | $\frac{\pi}{2}$ |
| ------------ | --- | -------------------- | -------------------- | -------------------- | --------------- |
| $\sin\theta$ | $0$ | $\frac{1}{2}$        | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ | $1$             |
| $\cos\theta$ | $1$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$        | $0$             |
| $\tan\theta$ | $0$ | $\frac{\sqrt{3}}{3}$ | $1$                  | $\sqrt{3}$           | $\pm\infty$     |
$\cos^2\theta+\sin^2\theta = 1$

 ### **Formules d'addition :**
- $\sin a+b=\sin a\cos b+\sin b\cos a$
- $\sin a-b = \sin a\cos b - \sin b\cos a$
- $\cos a+b = \cos a+\cos b - \sin a \sin b$
- $\cos a-b=\cos a \cos b + \sin a \sin b$
