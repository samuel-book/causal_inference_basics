# General notes

## Conditional probability

Conditional probability is the probability of one event, given that another has occurred.

P(X|Y) is the probability of X, given Y, though strictly this should be written as P(X=x|Y=y).

## Types of variables

*Endogenous variables* are observed variables.

*Exogenous variables* are unmeasured variables, though they may often be the *parents* of endogenous variables. Exogenous variables may also be called *noise variables*.

Most causal analysis assumes that exogenous variables are uncorrelated with each other, otherwise they become unobserved confounders. This assumption may often be a difficulty in real-world causal inference.

## Assignment

The *walrus operator* := signifies assignment, e.g. A:=f(U0) (the value of A is attributed to a function of the unobserved variable, U0).
