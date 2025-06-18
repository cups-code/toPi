---
tags:
  - Academics/Math
lesson: 3
math-topic: Topic 3 - Probability (Chapter 8, Y10)
math-type: Path
created: 2025-06-03
published: 2025-06-16
title: L03 - Mutually and Non-Mutually Exclusive Events
description: A conceptual document about Mutually & Non-Mutually Exclusive Events.
---
# Mutually and Non-Mutually Exclusive Events
## Learning Intentions
- I can apply the addition rule.
- I can use the addition rule.
## Definition of Mutually Exclusive Events
- Mutually exclusive events mean that both outcomes are exclusive to each other, meaning there is no overlap.
	- Mutually = both
	- Exclusive = excluding, separate
- $A \cap B = \emptyset = \{\}$

> [!example] Example of Mutually Exclusive Events
> - Let's take the sample space of rolling a standard six-sided die.
> 	- If outcome A = odd numbers and
> 	- outcome B = even numbers, 
> 	- then $A \cap B = \{\}$ (mutually exclusive, see the [[#Definition of Mutually Exclusive Events|definition]].)

## Definition of Non-Mutually Exclusive Events
- Non-mutually exclusive events mean that both outcomes are *not* exclusive to each other, meaning there is no overlap.
- $A \cap B \neq \emptyset$

> [!example] Example of Mutually Exclusive Events
> - Let's take the sample space of rolling a standard six-sided die.
> 	- If outcome A = odd numbers and
> 	- outcome B = even numbers, 
> 	- then $A \cap B = \{\}$ (mutually exclusive, see the [[#Definition of Mutually Exclusive Events|definition]].)

## The Addition Rule

> [!info] The Addition Rule
> $$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
> - This works by adding the probability of the two outcomes (which overlap) and subtracting the overlap.
> - $P(A \cap B)$ is ignored in a [[#Definition of Mutually Exclusive Events|mutually exclusive]] scenario.

> [!example] Standard Application of The Addition Rule (1)
> - A card is selected from a standard deck of 52 playing cards (no jokers). Find $P(A \cup B)$.
> 	- A = card of diamonds
> 	- B = jack card
> - $P(A) = \frac{1}{4}$ , $P(B) = \frac{1}{13}$, $P(A \cap B) = \frac{1}{52}$
> - Apply the [[#The Addition Rule|addition rule]] to find $P(A \cup B)$.
> 
> $$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
> 
> $$P(A \cup B) = \frac{1}{4} + \frac{1}{13} - \frac{1}{52} = \frac{13+4-1}{52}$$

> [!example] Standard Application of The Addition Rule (2)
> - Two events, A and B, are such that
> 	- $P(A) = 0.4$
> 	- $P(B) = 0.8$
> 	- $P(A \cup B) = 0.85$
> - Find (a) $P(A \cap B)$ and (b) $P(A' \cap B')$.
> - (a) $P(A \cap B)$ = 0.35 
> 	- $P(A) + P(B) = 0.4 + 0.8 = 1.2$
> 	- $P(A \cup B) = 1.2 \space \fbox{P(A) + P(B)}$
> 	- $P(A \cap B) = 1.2 - 0.85$
> 	- $\therefore P(A \cap B) = 0.35$
> - (b) $P(A' \cap B') = 0.15$
> 	- $1 - 0.85 = 0.15$ (anything not A and not B, complement!)


