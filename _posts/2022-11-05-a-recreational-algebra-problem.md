---
title: A recreational algebra problem
date: 2022-11-05 00:00 +0100
categories: [Math, Algebra]
tags: [problems]
math: true
image:
  path: /posts/20221105/problem.jpg
  width: 400
  height: 400
  alt: A recreational algebra problem to launch this blog.
---

## Description

Adaptation of a problem I found on Twitter[^footnote]. It is not very complicated but it is fun to solve and I think it is a good post to start this blog.

## Answer

> To solve this problem, let's start from a more general version, knowing that 

$$ 1000 = 2·500 $$

> Taking $$ 500 = a $$ we can write the problem as follows

$$ \frac{1000^{1000}}{500^{500}} \to \frac{(2a)^{2a}}{a^a} $$

> From here we solve the problem by applying the properties of powers[^fn-nth-2]

$$ \frac{(2a)^{2a}}{a^a} = \frac{2^{2a}·a^{2a}}{a^a} = 2^{2a}·\frac{a^{2a}}{a^a} = 2^{2a}·\frac{a^{2a}}{a^a} = $$

$$  = 2^{2a}·a^{2a-a} = 2^{2a}·a^{a} = 2^{2a}·a^{a} = (2^{2})^{a}·a^{a} $$

$$ = (2^{2}·a)^{a} = (4·a)^{a} $$

> Taking back $$ a = 500 $$ we obtain the solution to the problem

$$ = (4·a)^{a} \to (4·500)^{500} = (2000)^{500} $$

## Credits

[^footnote]: [Original problem](https://twitter.com/bbyboom/status/1581792329215590401/photo/1)
[^fn-nth-2]: [Power properties](https://www.problemasyecuaciones.com/potencias/potencias-ejemplos-ejercicios-resueltos-calcular-propiedades-producto-cociente-simplificar-exponente-base-multiplicar.html)