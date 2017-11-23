\PassOptionsToPackage{usenames,dvipsnames}{xcolor}

\documentclass[12pt,letterpaper]{book}

%Packages
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[english]{babel}
\usepackage{amsfonts}
\usepackage{amsthm}
\usepackage{mathtools}
\usepackage{amssymb}
\usepackage{mathrsfs}
\usepackage{cancel}
\usepackage{emptypage}
\usepackage{graphicx}
\usepackage{multirow}
\usepackage[all]{xy}
\usepackage[margin=2.5cm, headheight=20pt]{geometry}
\usepackage{eso-pic}
\newcommand\BackgroundPic{%
	\put(-210,340){%
		\parbox[b][\paperheight]{\paperwidth}{%
			\vfill
			\centering
			\includegraphics[scale=0.15,			keepaspectratio]{Escudo_unal_2016.png}%
			\vfill
}}}
\usepackage{fancyhdr}
\usepackage{enumerate}

\pagestyle{fancy}
\fancyhf{}
\fancyhead[LO]{  {\fontsize{8}{5}\textsl{\rightmark}}}
\fancyhead[RO]{  {\fontsize{8}{5}\selectfont Daniela \textsc{Martinez}} }
\fancyhead[RE]{ { \fontsize{8}{5} \textsl{\leftmark}}}
\fancyhead[LE]{ {\fontsize{8}{5} \selectfont Camilo  \textsc{Arias} }}
\fancyfoot[C]{\thepage}

\renewcommand{\headrulewidth}{1.5pt}


\usepackage{tikz}
\usetikzlibrary{cd,lindenmayersystems,arrows.meta,decorations.pathmorphing,decorations.markings,intersections}
\usepackage{imakeidx}
\makeindex[columns=2, title=Index, intoc]

%\PassOptionsToPackage{usenames,dvipsnames}{xcolor}
%\usepackage[usenames,dvipsnames]{xcolor}
\usepackage{tcolorbox}
\usepackage{fix-cm}
\usepackage{latexsym}
\usepackage{pb-diagram}
\usepackage{amsmath,amscd}
\usepackage{layout}
\usepackage{verbatim}
\usepackage{alltt}
\usepackage{bbm}
\usetikzlibrary{matrix,arrows,decorations.pathmorphing}
\usepackage{upgreek}
\usepackage{tikz-cd}
\usetikzlibrary{cd}
\usepackage{multicol}
\usepackage[hidelinks]{hyperref}



\newtheorem{theorem}{Theorem}[section]
\newtheorem{lemma}[theorem]{Lemma}
\newtheorem{proposition}[theorem]{Proposition}
\newtheorem{num}[theorem]{}
\newtheorem{corollary}[theorem]{Corollary}
\newtheorem{definition}[theorem]{Definition}
\theoremstyle{definition}
\newtheorem{example}[theorem]{Example}
\newtheorem{exercise}{Exercise}
\newtheorem{remark}[theorem]{Remark}
\newtheorem{axiom}{Axiom}
\newtheorem{note}{Note}
\newtheorem{conventions}{Conventions}
\newtheorem{free}{}
\newtheorem{notation}{Notation}
\newtheorem{obs}{Observation}
\newtheorem{observation}{Observation}
\newtheorem*{conjecture}{Conjecture}
\newtheorem*{theoremnn}{Theorem}
\newtheorem*{acknowledgements}{Acknowledgements}
\newcommand{\rmap}{\longrightarrow}
\newcommand{\Rep}{\textrm{Rep}}
\newcommand{\Der}{\textrm{Der}}
\newcommand{\RRep}{\mathcal{R}\textrm{ep}^{\infty}}
\newcommand{\URRep}{\mathcal{\hat{R}}\textrm{ep}^{\infty}}
\newcommand{\DDer}{\mathbb{D}\textrm{er}}
\newcommand{\pr}{pr}
\newcommand{\nor}{\mathrm{nor}}
\newcommand{\diff}{\mathrm{diff}}
\newcommand{\Ad}{\mathrm{Ad}}
\newcommand{\ad}{\mathrm{ad}}
\newcommand{\hPsi}{\hat{\Psi}}
\newcommand{\hR}{\hat{R}}
\newcommand{\hOmega}{\hat{\Omega}}
\newcommand{\id}{\mathrm{id}}
\newcommand{\End}{\textrm{End}}
\newcommand{\Hom}{\textrm{Hom}}
\newcommand{\RHom}{\underline{\mathrm{Hom}}}
\newcommand{\Lie}{\textrm{Lie}}
\newcommand{\smooth}{\mathcal{C}^{\infty}}
\newcommand{\Path}{\mathsf{P}}
\newcommand{\ev}{\textrm{ev}}
\newcommand{\Hoch}{\textrm{Hoch}}
\newcommand{\Chen}{\mathsf{C}}
\newcommand{\B}{\mathsf{B}}
\newcommand{\R}{\mathbb{R}}
\newcommand{\RR}{\ensuremath{\mathbb R}}
\newcommand{\MC}{\ensuremath{\mathbb C}}
\newcommand{\can}[1]{\ensuremath \cancelto{\mbox{\footnotesize 0}}{#1}}

\begin{document}
%\input{HojaTitulo/capa_novia}
\tableofcontents
\chapter{Introduction}
%\input{Cap1/cap1}
\chapter{Milnor's inequalities and the conjecture in dimension $d=2$}
%\input{Cap2/cap2}
\chapter{The counterexamples of Smillie}
%\input{Cap3/cap3}
\chapter{The case of complete manifolds, after Sullivan and Kostant}
%\input{Cap4/cap4}
\chapter{Appendix}
%\input{Anexos/Anexos}

\thebibliography{10}

\bibitem{B}
J.P. Benzecri, {\em Vari\'et\'es localment plates}, Ph.D thesis, Princeton University 1955.
\bibitem{BT}
R. Bott, L. Tu, {\em Differential forms in algebraic topology}, Graduate Texts in Mathematics, Springer Verlag, 1982.
\bibitem{Bu}
D. Burde, {\em Left invariant affine structures on nilpotent Lie groups}, Habilitationsschrift, D\"usseldorf, 1999.
\bibitem{FZ}
H. Feng and W. Zhang,
{\em Superconnections and affine manifolds},  arxiv:1603.07248.
\bibitem{Chern}
Chern, Shiing-Shen  { \em On the curvatura integra in Riemannian manifold}, Annals of Mathematics, 46 (4): 674-684.

\bibitem{Goldman1}
W. Goldman,
{\em Two papers that changed my life: Milnor's seminal work on flat manifolds and flat bundles}, arxiv:1108.0216 in Celebration of Milnor's 80 birthday.

\bibitem{Goldman2}
W. Goldman
{\em Geometric structures on manifolds}, Lecture notes available at http://www.math.umd.edu/~wmg/work.html.

\bibitem{Hirsch}
M. Hirsch, {\em Differential Topology}, Graduate Texts in Mathematics, Springer Verlag, 1976.
\bibitem{KS}
B. Kostant and D. Sullivan,
{\em The Euler characteristic of an affine space form is zero},
Bull. Amer. Math. Soc. 81 (1975), no.5, 937-938.
\bibitem{riemannian}
J. Lee, {\em Riemannian manifolds: an introduction to curvature}, Graduate Texts in Mathematics, Springer Verlag (1997).
\bibitem{Milnor}
J. Milnor,
{\em On the existence of a connection with curvature zero}, Comment. Math. Helv. 32 (1958),
215-223.
\bibitem{Milnor2}
J. Milnor, {\em On fundamental groups of complete affinely flat manifolds}, Advances in Math. 25
(1977), 178-187.
\bibitem{MS}
J. Milnor, J. Stasheff, {\em Characteristic classes}, Princeton University Press, 1974.
\bibitem{K}
B. Klingler,
{\em Chern's conjecture for special affine manifolds}, Annals of Mathematics 186 (2017), 1-27.

\bibitem{Smillie}
J. Smillie,
{\em Flat manifolds with non-zero Euler characteristics}, Comment. Math. Helv. 52 (1977),
no.3, 453-455.


\printindex 
\end{document}
