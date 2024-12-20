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
{% include mathjax.html %}
\begin{document}

\Mainmatter

\begin{frontmatter}

\chapter{Chapter Title}
% Enter author names EXACTLY as you would like them to appear in the final manuscript; only use pattern: first name, last name. Do NOT use pattern: last name, first name. Patronyms fall into the first name category.
\author{Author 1}
\author{Author 2}
\author{Author 3}

\makechaptertitle

\chaptermark{Chapter Title (will appear in header)}

\begin{abstract} % abstract = max 200 words, unstructured format, single paragraph
The abstract MUST be \textbf{unstructured}, in a \textbf{single paragraph}, and briefly introduce the manuscript, not exceeding \textbf{200 words}. Citations must NOT be included in the abstract. Any abstracts spanning multiple paragraphs will be converted into single-paragraph abstracts during typesetting.
\end{abstract}

\begin{keywords} % use a minimum of 5 kwrds, separate them with a comma
kwrd 1, kwrd 2, kwrd 3, kwrd 4, kwrd 5
\end{keywords}


\end{frontmatter}



\section{Introduction} % first section MUST be titled Introduction, and feature introductory text; do NOT change this title

The introduction section should provide a context for your manuscript and should be numbered as first heading. When preparing the introduction, please bear in mind that some readers will not be experts in your field of research.

\section{Body of the manuscript}

The body is where the author explains experiments, presents and interprets data of one's research. Authors are free to decide how the main body will be structured. However, you are required to have \textbf{at least one heading}. Please ensure that either British or American English is used consistently in your chapter.

The text throughout the manuscript will be \textbf{left-aligned (or ragged-right)} in the final version of the chapter. This is not a typesetting error. This cannot be changed on an individual basis, i.e. IntechOpen will not accept requests for custom text alignment. All chapters, in all publications, will have the same layout and formatting.

\subsection{Sub-sections}

Your chapter can have subsections along with main sections. Structurally, subsections cannot exists without their parent section.

\subsubsection{Sub-subsections}

Sub-subsections can also be used throughout the manuscript.

\section{How to prepare a chapter -- a brief guide}

\subsection{Citing sources}

When you are citing sources, the citations should be set in \textbf{numbered format}. All the references given in the list of references must be cited in the body of the text. Please set citations in square brackets keeping the below points in mind:

Correct format: [4-6, 9] or [4, 5, 6, 9]; [1, 2]

Incorrect format: [4-6,9]; [4] [5] [6] [9]; [1-2]

The numbers must be listed in sequential order, starting from number 1. That is, the first cited reference cannot be [2], or [5], or [48].

	\textbf{Note:} Author-Year referencing (i.e.: Smith et al., 2018) is NOT accepted.

\subsection{Figures and tables}

\textbf{Important!} To reuse figures and tables that have already been published elsewhere you are required to obtain permission from the copyright owner(s), for both the print and online format.

Both figures and tables must be cited in the main text of the chapter. That is, if a figure or table is placed somewhere in the body of the chapter, it must also be mentioned in the same text.

Examples:

\textbf{Figure 1} shows the results of the experiment.

The results of the study are shown in \textbf{Table 1}.

Experiments confirm the initial hypothesis (\textbf{Table 1}).

\subsubsection{Instructions for figures}

\begin{figure}[!b]\centering
	\FIG{\includegraphics[width=0.5\textwidth,height=12pc]{Image}}
	{\caption{Caption goes here. Captions will always be left-aligned and in italics in the final version of the professionally formatted chapter\label{ch02:fig01}}}
\end{figure}

Figures must be high resolution (300 DPI or higher). Acceptable image formats are .JPEG, .PNG, .TIFF, .BMP, .EPS, .WMF, .EMF or .PDF. Make sure to number your figures accordingly. Figures should not exceed 130mm (5,118 inches) in width, and 184 mm (7,244 inches) in height. Larger figures will be resized to fit within the appropriate dimensions.

Figures must be accompanied by captions. If not part of the figure, figure legend is to be placed beneath figure caption. When referring to a figure in the body of the text, the full word “Figure” is used. The order of main citations of figures in the text must be sequential.

Correct: Figure 1, Figure 2
Incorrect: Fig 1.1, Figure 1.1

\textbf{Note:} In the final manuscript, as a general layout rule, figures will be moved to either the top or the bottom of the page. Exceptions are possible in special cases, depending on the figure and the layout requirements.

An example of a figure is shown one on the previous page \textbf{(Figure 1)}.

\subsubsection{Instructions for tables}

\begin{table}[t]
	\TBL{\caption{Caption goes here. Captions will always be left-aligned and in italics in the final version of the professionally formatted chapter.}}
	{\begin{tabular*}{\textwidth}{@{\extracolsep{\fill}}@{\hspace*{5mm}}lccc}
			\toprule
			\TCH{Data} & \TCH{Present value (\%)\footnotemark{a}} & \TCH{Target} & \TCH{Percentage\footnotemark{b}}\\
			& & \TCH{(\%)} &\\
			\midrule
			Data 1 &  60 & 100 & 60/100\\\hline
			Data 2 &  78 & 100 & 78/100\\\hline
			Data 3 &  50 & 100 & 50/100\\\hline
			Data 4 &  70 & 100 & 70/100\\\hline
			Data 5 &   &  & 64.5/100\\
			\botrule
	\end{tabular*}}{\begin{tablenotes}
			\footnotetext[a]{This is a tablenote}
			\footnotetext[b]{This is another tablenote}
	\end{tablenotes}}
\end{table}

Tables must not be submitted as image formats (i.e. .jpeg, .tiff). As a rule, all tables must be in Portrait orientation and must be max 130mm (5,118 inches) wide.
\end{backmatter}


\end{document} 
