---
layout: post
title: Ensembles usuels et intervalles
toc: true
pin: false
math: true
tags: ["maths", "Niveau 2nde"]
---

## Ensembles

Tout d'abord, nous allond devoir définir ce qu'est un ensemble.

Une définition courante est la suivante : un ensemble est un regroupement d'objets mathématiques. On appelle élément d'un ensemble les objets en faisant partie.

> Ainsi, on peut voir un ensemble comme une sorte de boîte, qui contiendrait divers éléments (nombres, autres ensembles, etc)
{: .prompt-tip }


 Les ensembles ne "sont pas sensibles à la multiplicité et à l'ordre des éléments". En termes plus simples, cela signifie que l'ordre des éléments d'un ensemble et le fait que ceux-ci y soient présents plusieurs fois n'ont pas d'impact.
 Un ensemble qui contiendrait $a$ et $b$ serait ainsi le même qu'un ensemble contenant $b$ et $a$, et un ensemble contenant deux fois est exactement identique à un ensemble contenant $a$.


Pour dire qu'un élément $x$ appartient à un ensemble $X$, on note $x \in X$.


Pour que deux ensembles $X$ et $Y$ soit égaux, il faut que pour tout élément $x$, la relation $x \in X \iff x \in Y$ soit vérifiée, c'est-à-dire que si un élément $x$ appartient à l'ensemble $X$, alors il appartient également à l'ensemble $Y$, et inversement.

## Ensembles usuels 


On appelle ensembles usuels les ensembles les plus courants.

### L'ensemble des entiers naturels

On appelle entier naturel les nombres entiers positifs : 1, 2, 3, etc, ainsi que 0.

L'ensemble de ces nombres se note $\mathbb{N}$. Ainsi, on a $1 \in \mathbb{N}$, $57432 \in \mathbb{N}$, etc.

### L'ensemble des entiers relatifs

On appelle entier relatif tout nombre entier positif, négatif ou nul. 

L'ensemble de ces nombres se note $\mathbb{Z}$ (cette dénomination vient de l'allemand "die Zahl").
Ainsi, on a $-12 \in \mathbb{Z}$, $435 \in \mathbb{Z}$, mais aussi $14 \in \mathbb{Z}$. De manière générale, l'ensemble $\mathbb{Z}$ est l'ensemble des entiers naturels et des entiers négatifs. On peut donc noter : $\mathbb{N} \subset \mathbb{Z}$, ce qui signifie que l'ensemble $\mathbb{N}$ est inclus dans $\mathbb{Z}$.

### L'ensemble des nombres décimaux

On appelle nombre décimal tout nombre pouvant s'écrire avec un nombre fini de décimales. 1,25 en est un, car son nombre de décimales est fini. 1,33333... n'en est cependant pas un, car sa partie décimale se compose d'une infinité de 3.

On note cet ensemble $\mathbb{D}$. Comme précédemment, on a $\mathbb{N} \subset \mathbb{Z} \subset \mathbb{D}$.



### L'ensemble des nombres rationnels

On appelle nombre rationnel tout nombre qui peut s'écrire sous la forme d'une fraction de nombres entiers. Ainsi, 1,3333... pouvant s'écrire 4/3, il en fera partie.

On note cet ensemble $\mathbb{Q}$, avec $\mathbb{N} \subset \mathbb{Z} \subset \mathbb{D} \subset \mathbb{Q}$.

### L'ensemble des nombres réels

Un nombre irrationnel est un nombre ne pouvant pas s'écrire sous forme de fraction de nombres entiers, comme $\pi$ par exemple. 

L'ensemble des nombres réels est l'ensemble contenant à la fois les nombres rationnels et irrationnels. Il se note $\mathbb{R}$. On retrouve toujours la relation $\mathbb{Q}$, avec $\mathbb{N} \subset \mathbb{Z} \subset \mathbb{D} \subset \mathbb{Q} \subset \mathbb{R}$.

## Modifications d'ensembles


On applique parfois à ces ensembles certaines modifications, comme retirer le 0 ou ne considérer que les nombres positifs/négatifs.

Pour ne considérer que les nombres positifs d'un ensemble $X$, on note $X^+$. De même, pour n'en considérer que les nombres négatif, on note $X^-$. Pour en exclure 0, on note $X^*$, $X_0$ ou bien $X \setminus \\{ 0 \\}$.

Plus généralement, pour exclure un ensemble $Y$ d'un ensemble $X$, on note $X \setminus \\{Y\\}$. 


## Réunions et intersections

### Réunion

La réunion de deux ensembles (ou intervalles) représente l'ensemble des éléments appartenant à au moins un des deux ensembles. La réunion de deux ensembles $X$ et $Y$ se note $X \cup Y$.

### Intersection

L'intersection de deux ensembles (ou intervalles) représente l'ensemble des éléments appartenant **aux deux** ensembles. La réunion de deux ensembles $X$ et $Y$ se note $X \cap Y$.

## Intervalles de nombres entiers

On a vu que $\]x;y\[$ désignait l'ensemble des réels entre $x$ et $y$. Cependant, on peut parfois ne vouloir parler que des nombres entiers entre $x$ et $y$. 

Comme vu avant, on peut noter ceci sous la forme de l'intersection entre les entiers relatifs et l'intervalle (soit $]x;y[ \cap \mathbb{Z}$). Cependant, il existe une autre notation : $]\\!]x;y[\\![$. Attention tout de même à bien utiliser des crochets normaux, et non pas des doubles crochets, à une extrémité de $\infty$ ou $-\infty$.

## Intervalles de réels

- $x < y < z$ se note $y \in \]x;z\[$. On lit "$y$ appartient à l'intervalle ouverte de $x$ à $z$.

- $x \leq y \leq z$ se note $y \in \[x;z\]$. On lit "$y$ appartient à l'intervalle fermée de $x$ à $z$.

- $x \leq y < z$ se note $y \in \[x;z\[$

- $x < y \leq z$ se note $y \in \]x;z\]$

On peut également utiliser $+ \infty$ et $- \infty$ comme extrémités d'une intervalle.
Par exemple, $x > y$ se noterait $x \in \]y; + \infty[$.


> En utilisant $+ \infty$ ou $- \infty$ comme l'une des extrémités de l'intervalle, les crochets doivent impérativement être ouverte à cette extrémite.
{: .prompt-warning }