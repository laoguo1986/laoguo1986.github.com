---
layout: post
title: 幻灯片制作
categories:
- 技术控
tags:
- markdown
- beamer
- pandoc
---

md模板
>
% File Name
% Author Name
% \today 
~~~~~~~
## Outline
\tableofcontents

# Section 1

## First Slide

* Level 1-1 **strong emphasis** or *emphasis*

    + Level 2-1

    + Level 2-2 Math $B(t)\sim Poisson(\lambda_t)$

        - Level 3-1
        - Level 3-2

* Level 1-2

## Second Slide: Figure and footnote

* Insert Figures in this slide:

\centerline{\includegraphics[height=1.5in]{fig.png}}

Here is a footnote reference,[^1] and another.[^longnote]

[^1]: Here is the footnote.

[^longnote]: Here's one with multiple blocks.

## Third Slide: tables

  Right     Left     Center     Default
  -------     ------  ----------     -------
      12     12        12            12
    123     123     123           123
        1     1           1             1

Table:  Demonstration of simple table syntax.

# Section 2

## Fouth Slide: Two column

\begin{columns}[c]
\column{1.5in}
Practical \TeX\ 2005\\
Practical \TeX\ 2005\\
Practical \TeX\ 2005

\column{1.5in}
\framebox{\includegraphics[width=1.5in]{fig.png}}
\end{columns}
~~~~~~~
