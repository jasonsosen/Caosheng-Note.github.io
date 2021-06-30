---
layout: post
title: Flake it till you make it
subtitle: Excerpt from Soulshaping by Jeff Brown
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [books, test]
---

Under what circumstances should we step off a path? When is it essential that we finish what we start? If I bought a bag of peanuts and had an allergic reaction, no one would fault me if I threw it out. If I ended a relationship with a woman who hit me, no one would say that I had a commitment problem. But if I walk away from a seemingly secure route because my soul has other ideas, I am a flake?

The truth is that no one else can definitively know the path we are here to walk. It’s tempting to listen—many of us long for the omnipotent other—but unless they are genuine psychic intuitives, they can’t know. All others can know is their own truth, and if they’ve actually done the work to excavate it, they will have the good sense to know that they cannot genuinely know anyone else’s. Only soul knows the path it is here to walk. Since you are the only one living in your temple, only you can know its scriptures and interpretive structure.

At the heart of the struggle are two very different ideas of success—survival-driven and soul-driven. For survivalists, success is security, pragmatism, power over others. Success is the absence of material suffering, the nourishing of the soul be damned. It is an odd and ironic thing that most of the material power in our world often resides in the hands of younger souls. Still working in the egoic and material realms, they love the sensations of power and focus most of their energy on accumulation. Older souls tend not to be as materially driven. They have already played the worldly game in previous lives and they search for more subtle shades of meaning in this one—authentication rather than accumulation. They are often ignored by the culture at large, although they really are the truest warriors.

A soulful notion of success rests on the actualization of our innate image. Success is simply the completion of a soul step, however unsightly it may be. We have finished what we started when the lesson is learned. What a fear-based culture calls a wonderful opportunity may be fruitless and misguided for the soul. Staying in a passionless relationship may satisfy our need for comfort, but it may stifle the soul. Becoming a famous lawyer is only worthwhile if the soul demands it. It is an essential failure if you are called to be a monastic this time around. If you need to explore and abandon ten careers in order to stretch your soul toward its innate image, then so be it. Flake it till you make it.
![equation](http://www.sciweavers.org/tex2img.php?eq=1%2Bsin%28mc%5E2%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=)

# Mathematics

## Null space discussion

Definition of $H_k$ and $U_k$ is showing below
$$
H_k = \begin{bmatrix} \bar{f}_{u(k-1)}^T\bar{f}_{x(k)}^T &\ \ \  \bar{F}_{u(k-1)}^T+\bar{f}_{u(k-1)}^T\bar{F}_{x(k)}^T\\\bar{f}_{u(k)}^T& \bar{F}_{u(k)}^T
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
