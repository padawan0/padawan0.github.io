---
title: "Post: Modified Date"
last_modified_at: 2016-03-09T16:20:02-05:00
categories:
  - Blog
tags:
  - Post Formats
  - readability
  - standard
---
<html>
<head>
  <title>Mi Página de Matemáticas</title>
  <script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
  </script>
</head>
<body>
  \begin{document}
\maketitle

Th\`eme: dimension d'un espace vectoriel, matrices, rang d'une appliction linéaire.

\section*{1. Question de cours}
\begin{qparts}
\item Montrer que toutes les bases ont même cardinal.

\item Montrer le théorème de la base incomplète: à partir de G génératrice et de L libre on peut former B base.

\item Montrer l'existence d'un supplémentaire en dimension finie.

\end{qparts}

\section*{2. Exercices}
\begin{qparts}

\item Montrer que tout endomorphisme de rang $r\geq 1$ est somme de $r$ endomorphismes de rang 1.

\item Soit $f:\mathbb{C[X]}\rightarrow\mathbb{C[X]}$ telle que $f(P)=P(X+1)-P(X)$. 
\subitem 1) Montrer que $f$ est linéaire
\subitem 2) Trouver le noyau de $f$
\subitem 3) Injectivité et surjectivité de $f$?
\subitem 4) Montrer qu'il existe une base de $\mathbb{C[X]}$ notée $(e_i)_{i\in\mathbb{N}}$, telle que: $\forall i\in\mathbb{N^*}, f(e_i)=e_{i-1}$
\subitem 5) Exprimer la matrice de la restriction de f à $\mathbb{C}_{n-1}[X]$ dans la base restreinte $(e_0,...,e_{n-1})$ \subitem et en déduire que cette restriction est nilpotente

\item{Sur les matrices de trace nulle:}
\subitem Soit $E$ un $\mathbb{K}$-ev de dimension finie $n\geq 2$ et $u$ un endomoprhisme de $E$.
\subitem 1) On suppose que: $\forall x\in E,$ $(x,u(x))$ est liée. Montrer que u est une homothétie
\subitem 2) En déduire que toute matrice de trace nulle est semblable à une matrice de coeficients \subitem  diagonaux nuls
\subitem 3) Soit $A\in M_n(\mathbb{K})$. Montrer l'équivalence entre: \subitem $(i)$ $tr(A)=0$
\subitem $(ii)$ $\exists U,V \in M_n(\mathbb{K}), A=UV-VU$
\subitem Indication: On pourra considérer l'image de $\phi:M\rightarrow MD-DM$ où $D=diag(i),i\in\llbracket 1,n\rrbracket$

\item Soit une forme linéaire $f$ vérifiant: $\forall X,Y\in M_n(\mathbb{K}),$ $f(XY)=f(YX)$. Montrer qu'il existe $\lambda\in\mathbb{K}$ tel que: $f=\lambda.tr$

\item{Sur les hyperplans de $M_n(\mathbb{K})$:}
\subitem 1) Montrer que $\Phi:A\rightarrow (M\rightarrow tr(AM))$ est un isomorphisme entre $M_n(\mathbb{K})$ et son dual.
\subitem 2) En déduire que tout hyperplan de $M_n(\mathbb{K})$ rencontre $GL_n(\mathbb{K})$

\item Montrer que la famille $(x\rightarrow |x-a|)_{a\in\mathbb{R}}$ est libre (à définir pour un ensemble non discret)

\item \subitem 1) Soit $f\in L(\mathbb{R}^3)$ telle que: $f^3=0$ et $f^2\neq 0$. Montrer qu'il existe une base de $\mathbb{R}^3$ telle que la matrice de $f$ dans cette base s'écrive: 
$$\begin{pmatrix}
0&1&0\\
0&0&1\\
0&0&0\\
\end{pmatrix}$$

\subitem 2) Soit $f\in L(\mathbb{R}^3)$ telle que: $f^2=0$ et $f\neq 0$. Montrer que f est de rang 1

\item{Sur l’indice de nilpotence:}
\subitem Soit $E$ un $\mathbb{K}$-ev de dimension finie $n\in\mathbb{N}$ et $u$ un endomoprhisme nilpotent de $E$, d'indice de nilpotence $k\in\mathbb{N}$.
\subitem 1) Montrer que $k\leq n$
\subitem 2) Montrer que $u$ ne peut être inversible
\subitem 3) Soient $u_1,..,u_n$ n endomorphismes nilpotents commutant 2 à 2. Montrer que $u_1\circ ..\circ u_n=0$

\item{Sur la formule de Grassman:}
\subitem
Soit $E$ un $\mathbb{K}$-ev et soient $S=(u_1,...,u_n)$ un système de vecteurs de $E$ et $S'=(u_1,...,u_p)$ extrait de S ($i.e: p\leq n$). Si l'on note $r=dim(S)$, montrer alors que: $dim(S')\geq r+p-n$

\item{Sur la supplémentarité:}
\subitem 
Soit E un espace vectoriel de dimension $n\geq 2$ et F et G deux sous-espaces vectoriels de E de dimension $p\leq n$.
Montrer que F et G admettent un supplémentaire commun.

\item Soit $E$ un $\mathbb{K}$-ev de dimension finie $n\in\mathbb{N}$ et $u$ et $v$ 2 endomoprhismes de $E$. 
\subitem 1) Montrer que: $rg(u\circ v)= rg(v)-dim(Im(v)\cap Ker(u))=rg(u)-n+dim(Im(v)+Ker(u))$
\subitem 2) En déduire: $rg(u)+rg(v)-n\leq rg(u\circ v)\leq min(rg(u),rg(v))$

\item Soit $E$ un $\mathbb{K}$-ev de dimension finie $n\in\mathbb{N}$ et $u$ un edomorphisme de $E$. Montrer qu'on peut écrire: $u=g\circ p$ avec $g$ inversible et $p$ projecteur


\end{qparts}

\end{document}
</body>
</html>
