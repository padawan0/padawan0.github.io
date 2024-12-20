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
  <script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
  </script>
</head>
<body>

  Thème: dimension d'un espace vectoriel, matrices, rang d'une appliction linéaire.

  <p>1. Question de cours</p>
  <ol>
    <li>Montrer que toutes les bases ont même cardinal.</li>
    <li>Montrer le théorème de la base incomplète: à partir de G génératrice et de L libre on peut former B base.</li>
    <li>Montrer l'existence d'un supplémentaire en dimension finie.</li>
  </ol>

  <p>2. Exercices</p>
  <ol>
    <li>Montrer que tout endomorphisme de rang \( r \geq 1 \) est somme de \( r \) endomorphismes de rang 1.</li>
    <li>
      Soit \( f : \mathbb{C}[X] \to \mathbb{C}[X] \) telle que \( f(P) = P(X+1) - P(X) \).
      <ol>
        <li>Montrer que \( f \) est linéaire.</li>
        <li>Trouver le noyau de \( f \).</li>
        <li>Injectivité et surjectivité de \( f \) ?</li>
        <li>Montrer qu'il existe une base de \( \mathbb{C}[X] \) notée \( (e_i)_{i \in \mathbb{N}} \), telle que : \( \forall i \in \mathbb{N}^*, f(e_i) = e_{i-1} \).</li>
        <li>Exprimer la matrice de la restriction de \( f \) à \( \mathbb{C}_{n-1}[X] \) dans la base restreinte \( (e_0, \dots, e_{n-1}) \) et en déduire que cette restriction est nilpotente.</li>
      </ol>
    </li>
    <li>
      Sur les matrices de trace nulle :
      <ol>
        <li>Soit \( E \) un \( \mathbb{K} \)-espace vectoriel de dimension finie \( n \geq 2 \) et \( u \) un endomorphisme de \( E \).</li>
        <li>On suppose que : \( \forall x \in E, (x, u(x)) \) est liée. Montrer que \( u \) est une homothétie.</li>
        <li>En déduire que toute matrice de trace nulle est semblable à une matrice de coefficients diagonaux nuls.</li>
        <li>Soit \( A \in M_n(\mathbb{K}) \). Montrer l'équivalence entre :
          <ol>
            <li>\( \text{tr}(A) = 0 \)</li>
            <li>\( \exists U, V \in M_n(\mathbb{K}), A = UV - VU \)</li>
          </ol>
          Indication : On pourra considérer l'image de \( \phi : M \to MD - DM \) où \( D = \text{diag}(i), i \in \llbracket 1, n \rrbracket \).
        </li>
      </ol>
    </li>
    <!-- Continúa el resto del contenido de los ejercicios aquí -->
  </ol>

</body>
</html>
