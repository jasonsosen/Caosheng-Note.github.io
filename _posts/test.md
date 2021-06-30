---
layout: post
title: Flake it till you make it
subtitle: Excerpt from Soulshaping by Jeff Brown
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [books, test]
---

![equation](http://www.sciweavers.org/tex2img.php?eq=1%2Bsin%28mc%5E2%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=)

# Mathematics

## Null space discussion

Definition of $H_k$ and $U_k$ is showing below
$$
H_k = 
\begin{bmatrix} \bar{f}_{u(k-1)}^T\bar{f}_{x(k)}^T &\ \ \  \bar{F}_{u(k-1)}^T+\bar{f}_{u(k-1)}^T\bar{F}_{x(k)}^T\\\bar{f}_{u(k)}^T& \bar{F}_{u(k)}^T
\end{bmatrix}
$$

$$
    U_k= \begin{bmatrix} 
    \bar{f}_{u(k-1)}^T &\bar{F}_{u(k-1)}^T\\
    \bar{f}_{u(k)}^T\bar{f}_{x(k)}^{-T}&\ \ \ \  -\bar{f}_{u(k)}^T\bar{f}_{x(k)}^{-T}\bar{F}_{x(k)}^T+\bar{F}_{u(k)}^T
    \end{bmatrix}
$$

Since we have that,
$$
\begin{align}
    % \begin{split}
        \left\{
\begin{array}{lr}
H_{i-1}U_i^{tT} = 0_N \ \ \ \ \ \ &and \\ 
H_{i-2}M_{i-1}U_i^{tT} = 0_N  \ \ \ \ \ \ &and \\
\vdots \ \ \ \ \ \ &and \\
H_{h}M_{h}\dots M_{i-1}U_i^{tT}  = 0_N&\\
        \end{array} \right.  
\end{align}
$$

For the first equation, we have 

$$
\begin{aligned}
    U_i N^r (H_{i-1})\neq 0_N
\end{aligned}
$$

Since $N^r (H_{i-1})$ can be calculated as 
$$
H_{i-1} =
\begin{bmatrix} \bar{f}_{u(i-2)}^T\bar{f}_{x(i-1)}^T &\ \ \  \bar{F}_{u(i-2)}^T+\bar{f}_{u(i-2)}^T\bar{F}_{x(i-1)}^T\\\bar{f}_{u(i-1)}^T& \bar{F}_{u(i-1)}^T
\end{bmatrix}
$$

$$
N^r(H_{i-1}) =
\begin{bmatrix} 
N^c(\bar{f}_{u(i-1)})\\N^c(\bar{F}_{u(i-1)})\Gamma
\end{bmatrix}
$$
Here,
$$
\begin{aligned}
    \bar{f}_{u(i-2)}^T\bar{f}_{x(i-1)}^TN^c(\bar{f}_{u(i-1)})+(\bar{F}_{u(i-2)}^T+\bar{f}_{u(i-2)}^T\bar{F}_{x(i-1)}^T)N^c(\bar{F}_{u(i-1)})\Gamma=0
\end{aligned}
$$
Since
$$
\bar{F}_{u(i-2)}^TN^c(\bar{F}_{u(i-1)}=0
$$
We have
$$
\begin{aligned}
    \bar{f}_{u(i-2)}^T\bar{f}_{x(i-1)}^TN^c(\bar{f}_{u(i-1)})+(+\bar{f}_{u(i-2)}^T\bar{F}_{x(i-1)}^T)N^c(\bar{F}_{u(i-1)})\Gamma=0
\end{aligned}
$$
