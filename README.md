\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage[English]{babel}
\usepackage{amsmath}
\usepackage{amsthm}
\usepackage{hyperref}
\usepackage{latexsym}
\usepackage{cleveref}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=red,linktocpage=true}
\date{}
\title{MTK466 Matematiksel Yazma Becerileri
Final Odevi}
\author{Duhan ...\footnote{∗Department of ... , ... University, ... , Ankara, TURKEY}}
\maketitle
\theoremstyle{plain}
\newtheorem{thm}{Lemma}[section]
\newtheorem{Proposition2.4}[thm]{Proposition}
\newtheorem{thm2}[thm]{Threorem}
\begin{document}
\begin{abstract}
    We derive total mean curvature integration formulas of a three co\-dimensional foliation $\mathcal{F}^{n}$ on a screen integrable half-lightlike submanifold, $M^{n+1}$ in a semi-Riemannian manifold $\overline{M}^{n+3}$. We give generalized differ\-ential equations relating to mean curvatures of a totally umbilical half\-lightlike submanifold admitting a totally umbilical screen distribution,
and show that they are generalizations of those given by [K. L. Duggal
and B. Sahin, Differential geometry of lightlike submanifolds, Frontiers in
Mathematics, Birkh\"auser Verlag, Basel, 2010].
\end{abstract}
\section{Introduction}
The rapidly growing importance of lightlike submanifolds in semi-Riemannian
geometry, particularly Lorentzian geometry, and their applications to mathematical physics–like in general relativity and electromagnetism motivated the
study of lightlike geometry in semi-Riemannian manifolds. More precisely, lightlike submanifolds have been shown to represent different black hole horizon (see ~\cite{4} and ~\cite{5} for details) Among other motivations for investing in lightlike geometry by many physicists is the idea that the universe we are living in can
be viewed as a 4-dimensional hypersurface embedded in $(4 + m)$-dimensional
spacetime manifold, where \mathcal{$m$} is any arbitrary integer. There are significant differences between lightlike geometry and Riemannian geometry as shown in ~\cite{4} and ~\cite{5},and many more references therein. Some of the pioneering work on this
topic is due to Duggal-Bejancu~\cite{4}, Duggal-Sahin~\cite{5} and Kupeli~\cite{7}.  It is upon
those books that many other researchers, including but not limited to ~\cite{3},~\cite{6},~\cite{8},~\cite{9},~\cite{10},~\cite{11}, have extended their theories.   
\section{Integration formulas for $\mathcal{F}$}
This section is devoted to derivation of integral formulas of foliation $\mathcal{F}$ of $S(TM)$ with a unit normal vector $\widehat{W}$. By the fact that $\overline{\nabla}$ is a metric conneciton then
\newpage
\noindent
$\bar{g}(\overline{\nabla}_{\widehat{W}}\widehat{W},\widehat{W}) = 0$.  This implies that the vector field $\overline{\nabla}_{\widehat{W}}\widehat{W}$ is always tan\-gent to $\mathcal{F}$. Our main goal will be to compute the divergence of the vectors $T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W}$ and $T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W}+(-1)^{r}S_{r+1}\widehat{W}$. The following technical lemmas are fundamentally important to this paper. Let $\{E,Z_{i},N,W\}$, for $i = 1,\cdots,n$ be
a quasi-orthonormal field of frame of $T\overline{M}$, such that $S(TM)$ = span$\{ Z_{i}\}$ and $\epsilon_{i}=\overline{g}(Z_{i},Z_{i})$.

\begin{thm}\label{2.1}
Let M be a screen integrable half-lightlike submanifold of $\overline{M}^{n+3}$ and let $M^'$ be a foliation  S(TM). Let $\mathcal{A}_{\widehat{W}}$ be its shape operator, where $\widehat{W}$ is a unit normal vector to $\mathcal{F}$. Then
\begin{align*}
    \overline{g}((\nabla_{X}^{'}\mathcal{A}_{\widehat{W}})Y,Z)&=\overline{g}(Y,(\nabla_{X}^{'}\mathcal{A}_{\widehat{W}})Z), \\
    \overline{g}((\nabla_{X}^{'}T_{r})Y,Z)&=\overline{g}(Y,(\nabla_{X}^{'}T_{r})Z), 
\end{align*}
for all X,Y,Z $\in$ $\Gamma(T\mathcal{F})$
\begin{proof}
By simple calculations we have
    \begin{equation}
        \overline{g}((\nabla_{X}^{'}\mathcal{A}_{\widehat{W}})Y,Z)=\overline{g}(\nabla_{X}^{'}(\mathcal{A}_{\widehat{W}}Y),Z)-\overline{g}(\nabla_{X}^{'}Y,\mathcal{A}_{\widehat{W}}Z).\label{eq:1}
    \end{equation}
    Using the fact that $\nabla^{'}$ is a metric connection and the symmetry of $\mathcal{A}_{\widehat{W}}$, \eqref{eq:1} gives
    \begin{equation}
        \overline{g}((\nabla_{X}^{'}\mathcal{A}_{\widehat{W}})Y,Z)=\overline{g}(Y,\nabla_{X}^{'}(\mathcal{A}_{\widehat{W}})Z))-\overline{g}(Y,\mathcal{A}_{\widehat{W}}(\nabla_{X}^{'}Z)). \label{eq:2}
    \end{equation}
    Then, from \eqref{eq:2} we deduce the first relation of the lemma. A proof of the second
relation follows in the same way, which completes the proof.
\end{proof}
\end{thm}
\begin{thm}\label{thm22}
Let M be a screen integrable half-lightlike submanifold of $\overline{M}$ and $\mathcal{F}$ be a co-dimension three foliation of S(TM). Let $A_{\widehat{W}}$ be its shape operator,
where $\widehat{W}$ is a unit normal vector to $\mathcal{F}$. Denote by $\overline{R}$ the curvature tensor of $\overline{M}$. \\ Then
    \begin{align*}
        div^{\nabla^{'}}(T_{0})&=0 \\ div^{\nabla^{'}}(T_{r})&=\mathcal{A}_{\widehat{W}}div^{\nabla^{'}}(T_{r-1})+\sum_{i=1}^{n}\in(\overline{R}(\widehat{W},T_{r-1}Z_{i})Z_{i})^{'}, 
    \end{align*}
where $(\overline{R}(\widehat{W},X)Z)'$  denotes the tangential component of $(\overline{R}(\widehat{W},X)Z$ for X,Z $\in\Gamma(T\mathcal{F})$. Equivalently, for any Y$\in\Gamma(T\mathcal{F})$ then
    \begin{equation}
        \overline{g}(div^{\nabla^{'}}(T_{r}),Y)=\sum_{j=1}^{r}\sum_{i=1}^{n}\in_{i}\overline{g}(\overline{R}(T_{r-1}Z_{i},\widehat{W})(-A_{\widehat{W}})^{j-1}Y,Z_{i}).\label{eq:3}
    \end{equation}
    \begin{proof}
    The first equation of the lemma is obvious since $T_{0}=\parallel$. We turn to the
second relation. By direct calculations using the recurrence relation we derive
        \begin{align}
            div^{\nabla^{'}}(T_{r})&=(-1)^{r}div^{\nabla^{'}}(S_{r}\parallel)+ div^{\nabla^{'}}(\mathcal{A}_{\widehat{W}} \circ T_{r-1})\nonumber\\
            &=(-1)^{r}\nabla^{'}S_{r}+\mathcal{A}_{\widehat{W}}div^{\nabla^{'}}(T_{r-1})+\sum_{i=1}^{n}\in_{i}(\nabla^{'}_{Z_{i}}\mathcal{A}_{\widehat{W}})T_{r-1}Z_{i} \label{eq:4}
        \end{align}
        Using Codazzi equation
        \begin{equation*}
            \overline{g}(\overline{R}(X,Y)Z,\widehat{W})=\overline{g}((\nabla^{'}_{Y}\mathcal{A}_{\widehat{W}})X,Z)-\overline{g}((\nabla^{'}_{X}\mathcal{A}_{\widehat{W}})Y,Z),
        \end{equation*}
        for any $X,Y,Z \in\Gamma(T\mathcal{F})$ and Lemma \ref{2.1}, we have
        \begin{align}
            \overline{g}((\nabla^{'}_{Z_{i}}\mathcal{A}_{\widehat{W}}Y,&T_{r-1}Z_{i})=\overline{g}((\nabla^{'}_{Y}\mathcal{A}_{\widehat{W}})Z_{i},T_{r-1}Z_{i})+\overline{g}(\overline{R}(Y,Z_{i})T_{r-1}Z_{i},\widehat{W})\nonumber \\ &=\overline{g}(T_{r-1}(\nabla^{'}_{Y}\mathcal{A}_{\widehat{W}})Z_{i},Z_{i})+\overline{g}(\overline{R}(\widehat{W},T_{r-1}Z_{i})Z_{i},Y),\label{eq:5}
        \end{align}
        for any $Y\in \Gamma(T\mathcal{F})$ Then applying (\ref{eq:4}) and (\ref{eq:5}) we get
        \begin{align}
            \overline{g}(div^{\nabla^{'}}(T_{r}),Y)&=(-1)^{r}\overline{g}(\nabla^{'}S_{r},Y)+tr(T_{r-1}(\nabla^{'}_{Y}\mathcal{A}_{\widehat{W}}))\nonumber \\ + &\overline{g}(div^{\nabla^{'}}(T_{r-1}),Y)+\overline{g}(Y,\sum^{n}_{i=1}\in_{i}\overline{R}(\widehat{W},T_{r-1}Z_{i})Z_{i}).
        \end{align}
        Then we get the second equation of the lemma. Finally (~\ref{eq:3})  follows immediately
by an induction argument.
    \end{proof}
\end{thm}
Notice that when the ambient manifold is a space form of constant sectional
curvature, then $(\overline{R}(\widehat{W},X)Y)^{'})=0$ for each $X,Y\in \Gamma(T\mathcal{F})$. Hence from Lemma (\ref{thm22}) we have $div^{\nabla^{'}}(T_{r})=0$

\begin{thm}\label{lma-2}
Let M be a screen integrable half-lightlike submanifold of  $\overline{M}$ and let $\mathcal{F}$ be a co-dimension three foliation of S(TM). Let $\mathcal{A}_{\widehat{W}}$ be its shape operator,
where $\widehat{W}$ is a unit normal vector to $\mathcal{F}$. Let $\{ Z_{i} \} $ be a local field such $(\nabla_{X}^{'}Z_{i})p=0$ for $i=1,\cdots,n$ and any vector field $X\in \Gamma(T\overline{M})$. Then $p\in\mathcal{F}$ we have
\begin{align*}
 g(\nabla^{'}_{Z_{i}}\overline{\nabla}_{\widehat{W}}\widehat{W},Z_{j})&=g(\mathcal{A}^{2}_{\widehat{W}}Z_{i},Z_{j})-\overline{g}(\overline{R}(Z_{i},\widehat{W})Z_{j},\widehat{W})\\ &-g((\nabla^{'}_{\widehat{W}}\mathcal{A}_{\widehat{W}})Z_{i},Z_{j})+g(\overline{\nabla}_{\widehat{W}}\widehat{W},Z_{i})g(Z_{j},\overline{\nabla}_{\widehat{W}}\widehat{W}).   
\end{align*}
    \begin{proof}
    Applying $\overline{\nabla}_{Z_{i}}$ to $g(\overline{\nabla}_{\widehat{W}}\widehat{W},Z_{j})$ and $\overline{g}(\widehat{W},\overline{\nabla}_{\widehat{W}},Z_{j})$ in turn and then using
    the two resulting equations, we have
    \begin{align}
        -\overline{g}(\overline{\nabla}_{\widehat{W}}\widehat{W}\overline{\nabla}_{\widehat{Z_{i}}}Z_{j})&=g(\overline{\nabla}_{Z_{i}}\overline{\nabla}_{\widehat{W}}\widehat{W},Z_{j})+\overline{g}(\overline{\nabla}_{Z_{i}}\widehat{W},\overline{\nabla}_{\widehat{W}}Z_{j})\nonumber\\&+\overline{g}(\widehat{W},\overline{\nabla}_{Z_{i}}\overline{\nabla}_{\widehat{W}}Z_{j})\label{eq:7}.
    \end{align}
    Furthermore, by direct calculations using $(\nabla^{'}_{X}Z_{i})p=0$ we have
    \begin{equation*}
        \overline{g}((\nabla^{'}_{\widehat{W}}\mathcal{A}_{\widehat{W}})Z_{i},Z_{j})=\overline{g}(\overline{\nabla}_{\widehat{W}}\widehat{W},\overline{Z}_{i}Z_{j})+\overline{g}(\widehat{W},\overline{\nabla}_{\widehat{W}}\overline{Z}_{i}Z_{j}),
    \end{equation*}
    and hence
    \begin{align}
        g(\mathcal{A}^{2}_{\widehat{W}}Z_{i},Z_{j})&-\overline{g}(\overline{R}(Z_{i},\widehat{W})Z_{j},\widehat{W})-\overline{g}((\nabla^{'}_{\widehat{W}}\mathcal{A}_{\widehat{W}})Z_{i},Z_{j})\nonumber\\&=g(\mathcal{A}^{2}_{\widehat{W}}Z_{i},Z_{j})-\overline{g}(\overline{R}(Z_{i},\widehat{W})Z_{j},\widehat{W})\nonumber\\&-\overline{g}(\overline{\nabla}_{\widehat{W}}\widehat{W},\overline{Z}_{i}Z_{j})-\overline{g}(\widehat{W},\overline{\nabla}_{\widehat{W}}\overline{Z}_{i}Z_{j})\nonumber\\&=g(\mathcal{A}^{2}_{\widehat{W}}Z_{i},Z_{j})-\overline{g}(\overline{\nabla}_{Z_{i}}Z_{j},\overline{\nabla}_{\widehat{W}}\widehat{W})\nonumber\\&-\overline{g}(\overline{\nabla}_{Z_{i}}\overline{\nabla}_{\widehat{W}}Z_{j},\widehat{W})+\overline{g}(\overline{\nabla}_{[Z_{i},\widehat{W}]}Z_{j},\widehat{W})\label{eq:8}.
    \end{align}
    Now, applying (\ref{eq:7}) the condition at $p$ and the following relations
    \begin{equation*}
        \overline{\nabla}_{Z_{i}}\widehat{W}=\sum^{n}_{k=1}\in_{k}\overline{g}(\overline{\nabla}_{Z_{i}}\widehat{W},Z_{k})Z_{k}, \hspace{4}\overline{\nabla}_{\widehat{W}}Z_{j}=\overline{g}(\overline{\nabla}_{\widehat{W}}Z_{j},\widehat{W})\widehat{W},
    \end{equation*}
    and $g(\mathcal{A}^{2}_{\widehat{W}}Z_{i},Z_{j})=-\sum^{n}_{k=1}\in_{k}\overline{g}(\overline{\nabla}_{Z_{i}}\widehat{W},Z_{k})\overline{g}(\overline{\nabla}_{Z_{k}}Z_{j},\widehat{W})$  to the last line of (\ref{eq:8}) and the fact that $S(TM)$ is integrable we get
    \begin{align*}
        g(\mathcal{A}^{2}_{\widehat{W}}Z_{i},Z_{j})&-\overline{g}(\overline{R}(Z_{i},\widehat{W})Z_{j},\widehat{W})-\overline{g}((\nabla^{'}_{\widehat{W}}\mathcal{A}_{\widehat{W}})Z_{i},Z_{j})\\&=g(\nabla^{'}_{Z_{i}}\overline{\nabla}_{\widehat{W}}\widehat{W},Z_{j})-g(\overline{\nabla}_{\widehat{W}}\widehat{W},Z_{i})g(Z_{j},\overline{\nabla}_{\widehat{W}}\widehat{W}),
    \end{align*}
    from which the lemma follows by rearrangement.
    \end{proof}
\end{thm}
Notice that, using parallel transport, we can always construct a frame field
from the above lemma.
 \begin{Proposition2.4}\label{eq:2.4}
 Let M be a screen integrable half-lightlike submanifold of an
indefinite almost contact manifold $\overline{M}$ and let $\mathcal{F}$ be a foliation of S(TM). Thenr
    \begin{align*}
    div^{\nabla^{'}}(T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W})&=\overline{g}(div^{\nabla^{'}}(T_{r}),\overline{\nabla}_{\widehat{W}}\widehat{W})+(-1)^{r+1}\widehat{W}(S_{r+1})\\&+(-1)^{r+1}(-S_{1}S_{r+1}+(r+2)S_{r+2})-\sum^{n}_{i=1}\epsilon_{i}\overline{g}(\overline{R}(Z_{i},\widehat{W})T_{r}Z_{i},\widehat{W})\\&+\overline{g}(\overline{\nabla}_{\widehat{W}}\widehat{W},T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W}),
    \end{align*}
    where $ \{ Z_{i} \} $ is a field of frame tangent to the leaves of $\mathcal{F}$.
    \begin{proof}
    We deduce that
    \begin{equation}
        div^{\nabla^{'}}(T_{r}Z)=\overline{g}(div^{\nabla^{'}}(T_{r}),Z)+\sum^{n}_{i=1}\epsilon_{i}\overline{g}(\nabla^{'}_{Z_{i}}Z,T_{r}Z_{i})\label{eq:9},
    \end{equation}
    for all $Z\in \Gamma(T\mathcal{F})$. Then using (\ref{eq:9}), Lemmas \ref{thm22} and \ref{lma-2} we obtain the desired
result. Hence the proof.
    \end{proof}
 \end{Proposition2.4}
 From \ref{eq:2.4} we have
 \begin{thm2}
 Let M be a screen integrable half-lightlike submanifold of an
indefinite almost contact manifold $\overline{M}$ and let $\mathcal{F}$ be a co-dimension three foliationof S(TM). Then
\begin{align*}
    div^{\overline{\nabla}}(T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W})&=\overline{g}(div^{\nabla^{'}}(T_{r}),\overline{\nabla}_{\widehat{W}}\widehat{W})+(-1)^{r+1}\widehat{W}(S_{r+1})\\&+(-1)^{r+1}(-S_{1}S_{r+1}+(r+2)S_{r+2})\\&-\sum^{n}_{i=1} \epsilon_{i}\overline{g}(\overline{R}(Z_{i},\widehat{W})T_{r}Z_{i},\widehat{W}).
\end{align*}
\begin{proof}
 A proof follows easily from Proposition (\ref{eq:2.4}) by recognizing the fact that
 \begin{align*}
    div^{\overline{\nabla}}(T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W})&=div^{\nabla^{'}}(T_{r}\overline{\nabla}_{\widehat{W}}\widehat{W})\\&-\overline{g}(\overline{\nabla}_{\widehat{W}}\widehat{W},T_{r} \overline{\nabla}_{\widehat{W}}\widehat{W}), 
 \end{align*}
 which completes the proof.
\end{proof}
 \end{thm2}
 

\begin{thebibliography}{}
\bibitem{1}K. Andrzejewski, W. Kozlowski and K. Niedzialomski, {\em Generalized Newton
transformation and its applications to extrinsic geometry}, Asian J. Math.
 \boldmath{$20$}, no. 2, 293-322, 2016.
\bibitem{2}K. Andrzejewski and Pawel G. Walczak, {\em The Newton transformation and
new integral formulae for foliated manifolds}, Ann. Glob. Anal. Geom. \boldmath{$37$},
no. 2, 103-111, 2010.
\bibitem{3}
C. Calin, {\em Contributions to geometry of CR-submanifold}, Ph.D. thesis, Uni\-versity of Iasi (Romania), 1998.
\bibitem{4}
K. L. Duggal and A. Bejancu, {\em Lightlike submanifolds of semi-Riemannian
manifolds and applications, Mathematics and Its Applications}, Kluwer Aca\-demic Publishers, 1996.
\bibitem{5}
K. L. Duggal and B. Sahin, {\em Differential geometry of lightlike submanifolds.
Frontiers in Mathematics}, Birkh\"auser Verlag, Basel, 2010.
\bibitem{6}
K. L. Duggal and B. Sahin, {\em Screen conformal half-lightlike submanifolds},
Int. J. Math. Math. Sci. \boldmath{$2004$}, no. 68, 3737-3753, 2004.
\bibitem{7}
D.N. Kupeli, {\em Singuler semi-Riemannian geometry}, Mathematics and Its
Applications, Vol. \boldmath{$366$}, Kluwer Academic Publishers, 1996.
\bibitem{8}
F. Massamba, {\em Totally contact umbilical lightlike hypersurfaces of indefinite
Sasakian manifolds}, Kodai Math. J. \boldmath{$31$}, 338-358, 2008.
\bibitem{9}
F. Massamba, {\em On semi-parallel lightlike hypersurfaces of indefinite Ken\-motsu manifolds}, J. Geom. \boldmath{$95$}, 73-89, 2009.
\bibitem{10}
F. Massamba and S. Ssekajja, {\em Some remarks on quasi generalized CR-null
geometry in indefinite nearly cosymplectic manifolds}, Int. J. Math. Math.
Sci., Art. ID 9613182, 10 pp, 2016.
\bibitem{11}
E. Yasar, A. C. Coken, and A. Yucesan,{\em Lightlike hypersurfaces in semiRiemannian manifold with semi-symmetric non-metric connection}, Math.
Scand. \boldmath{$102$}, no. 2, 253-264, 2008.

\end{thebibliography}

\end{document}
