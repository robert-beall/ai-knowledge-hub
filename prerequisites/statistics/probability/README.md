# [Probability](https://seeing-theory.brown.edu/basic-probability/index.html)
- [Probability](#probability)
    - [Random Variable](#random-variable)
  - [Expectation](#expectation)
    - [Expectation Formula](#expectation-formula)
  - [Variance](#variance)
    - [Variance Formula](#variance-formula)
  - [Sources](#sources)

*Probability Theory* is a mathematical framework for analyzing chance events in a logically sound manner. The probability of an event is a number indicating how likely an event is to occur.<sup>[1](https://seeing-theory.brown.edu/basic-probability/index.html)</sup>.

The probability of an event is a number ranging from 0 to 1:
* 0 = Impossible
* 1 = Certain

### [Random Variable](https://seeing-theory.brown.edu/probability-distributions/index.html#section1)
A mathematical object where a real-number value is assigned to each possible outcome.

For example, take a coin toss: 
* heads = 1
* tails = 0

## Expectation
The expectation of a random variable is a number that attempts to capture the center of that random variable's distribution.

A more precise definition: **The probability weighted sum of all possible values in random variable's support**.

### Expectation Formula
> E[X]=∑x∈xP(x)

`E[X]` represents the expected value for random variable **X**.

Lowercase `x` represents all possible values within the random variable.

`P(x)` is the probability for each value x.

`Σ` denotes a sum of all terms.

## Variance
Variance quantifies the spread of a random variable's distribution.

Notes on variance<sup>[2](https://en.wikipedia.org/wiki/Variance)</sup>:
* Always positive number
* A higher variance indicates greater spread of values from the expectation.
* A lower variance indicates a smaller spread with values hewing closer to expectation.

### Variance Formula
Variance is the average value of the squared difference between the random variable and its expectation: 

>Var(X)=E[(X−E[X])<sup>2</sup>]

`Var(X)` is the variance of the random variable `X`.

`E[...]` denotes the expected value.

`E(X)` is the expectation of the random variable.

## Sources
1. [Seeing Theory - Probability Theory](https://seeing-theory.brown.edu/basic-probability/index.html)
2. [Variance - Wikipedia](https://en.wikipedia.org/wiki/Variance)