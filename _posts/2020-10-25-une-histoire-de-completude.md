---
layout: post
excerpt_separator: <!--more-->
title: Convergence de v.a. et lois faibles et fortes des grands nombres
description: La construction de $R$ par les suites de Cauchy 
permalink: completude/
date: 2020-10-25
---
$
\newcommand{\Pb}{\mathbb{P}}
\newcommand{\E}{\mathbb{E}}
\newcommand{\1}{\mathbf{1}}
\newcommand{\D}{\mathcal{D}}
\newcommand{\C}{\mathbb{C}}
\newcommand{\R}{\mathbb{R}}
\newcommand{\Q}{\mathbb{Q}}
\newcommand{\N}{\mathbb{N}}
\newcommand{\Z}{\mathbb{Z}}
\newcommand{\U}{\mathbb{U}}
\newcommand{\M}{\mathcal{M}}
\newcommand{\Sy}{\mathfrak{S}}
\newcommand{\B}{\mathcal{B}}
$

Soit $(\Omega, \B, \Pb)$ un espace probabilisé, $(X_n)_{n \geq 1), X$ des variables aléatoires réelles définies sur cet espace.
Lorsqu'on travaille avec des suites variables aléatoires réelles $X_n$, il peut être utile de définir des modes de convergence plus "souples" que ceux habituels : d'autant plus que l'étude des phénomènes asymptotiques (c'est à dire, quand on répète l'experience un grand nombre de fois), est particulièrement importante en probabilités. 

# Convergence en probabilité :

On dit que $(X_n)$ converge en probabilité vers $X$ lorsque, $\forall \varepsilon > 0$, on a :
$$
  \Pr(|X_n-X| > \varepsilon ) \underset{n \mapsto +\infty}{\longrightarrow} 0
$$




