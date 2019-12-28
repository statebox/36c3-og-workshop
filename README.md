# 36c3 workshop on Open Games

Open Games is a compositional framework for game theory.

It uses the mathematical theory of (monoidal) categories to describe games.

An introduction to category theory can be found in the [Statebox Monograph](https://papers.statebox.org/#/documents/monograph)

Elements of these things (called morphism) can be expressed as diagrams:

![](lemon-game-diagram.png)

We can use [tools developed at Statebox](https://edit.statebox.cloud) to build these diagrams and export Haskell `Arrow` expressions.

There is a [backend written in Haskell](https://github.com/jules-hedges/open-games-hs) that can do computations based on these diagrams / expressions.

In this workshop we will explain what this does and play around with the backend.
