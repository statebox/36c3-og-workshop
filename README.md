# 36c3 workshop on Open Games

> Workshop @ RIAT, Hall 2 ~ `Monday 14:30 - 16:00`

Open Games is a compositional framework for game theory.

It uses the mathematical theory of (monoidal) categories to describe games.

An introduction to category theory can be found in the [Statebox Monograph](https://papers.statebox.org/#/documents/monograph)

Elements of these things (called morphism) can be expressed as diagrams:

[![](lemon-game-diagram.png)](https://edit.statebox.cloud/#pixels=Nq---U%0ANqSp-U%0ANqSpBU%0ANqS--U&context=Nature%3A%20-%3E%20Q%0Aq%3A%20Q%20-%3E%20Q%20Q%0Ap%3A%20P%20-%3E%20P%20P%0ASeller%3A%20Q%20-%3E%20P%20R*%0ABuyer%3A%20P%20-%3E%20B%20R*%0AUtility%3A%20Q%20P%20B%20R*%20R*%20-%3E%0A)

We can use [tools developed at Statebox](https://edit.statebox.cloud) to build these diagrams and export Haskell `Arrow` expressions.

There is a [backend written in Haskell](https://github.com/jules-hedges/open-games-hs) that can do computations based on these diagrams / expressions.

In this workshop we will explain what this does and play around with the backend.

## Outline

- Explain general idea
  > Compositional game theory using category theory
  >
  > Applications: protocol verification
- what is a category (example)
- show monoidal category (in editor)
- explain open games