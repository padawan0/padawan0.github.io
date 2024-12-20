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
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documento LaTeX en Web</title>

    <!-- Cargar MathJax para procesar LaTeX -->
    <script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
    </script>

</head>
<body>

    <!-- Aquí puedes colocar el contenido de tu documento LaTeX, rodeado por un bloque script -->
    <script type="math/tex">
    \documentclass{article}
    \usepackage{amsmath,amsfonts,amssymb}

    \begin{document}

    \maketitle

    \textbf{Thème: dimension d'un espace vectoriel, matrices, rang d'une application linéaire.}

    \section*{1. Question de cours}

    \textbf{(a)} Montrer que toutes les bases ont même cardinal.

    \textbf{(b)} Montrer le théorème de la base incomplète: à partir de \( G \) génératrice et de \( L \) libre on peut former \( B \) base.

    \textbf{(c)} Montrer l'existence d'un supplémentaire en dimension finie.

    \section*{2. Exercices}

    \textbf{(a)} Montrer que tout endomorphisme de rang \( r \geq 1 \) est somme de \( r \) endomorphismes de rang 1.

    \textbf{(b)} Soit \( f: \mathbb{C}[X] \rightarrow \mathbb{C}[X] \) telle que \( f(P) = P(X+1) - P(X) \).

    \begin{enumerate}
      \item Montrer que \( f \) est linéaire.
      \item Trouver le noyau de \( f \).
      \item Injectivité et surjectivité de \( f \)?
      \item Montrer qu'il existe une base de \( \mathbb{C}[X] \) notée \( (e_i)_{i \in \mathbb{N}} \), telle que: \( \forall i \in \mathbb{N}^*, f(e_i) = e_{i-1} \).
      \item Exprimer la matrice de la restriction de \( f \) à \( \mathbb{C}_{n-1}[X] \) dans la base restreinte \( (e_0, ..., e_{n-1}) \) et en déduire que cette restriction est nilpotente.
    \end{enumerate}

    \end{document}
    </script>

</body>
</html>
