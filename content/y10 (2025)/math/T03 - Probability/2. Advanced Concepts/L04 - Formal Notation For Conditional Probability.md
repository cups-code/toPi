---
tags:
  - Academics/Math
lesson: 4
math-topic: Topic 3 - Probability (Chapter 8, Y10)
math-type: Path
date: 2025-06-16
---
# Formal Notation For Conditional Probability
## Basic Definition
> [!info] Conditional Probability
> $$P(A | B) = \fbox{probability of A given B}$$
> - $P(A | B)$ is defined as the probability of A **given** B.
> 	- This means that if we know B has already occurred, what is the probability of A?
## Formula
> [!info] Conditional Probability in Formal (Set) Notation
> 1. Probability of A given B
> $$P(A|B) = \frac{n(A \cap B)}{n(B)}$$
> 	$$= \frac{P(A \cap B)}{P(B)}$$
> 2. Probability of B given A
> $$P(B|A) = \frac{n(A \cap B)}{n(A)}$$
> 	$$= \frac{P(A \cap B)}{P(A)}$$
## Examples
> [!Example] Example 1
> 20 people, 15 are wearing *jackets*, 10 are wearing *hats*.
> 1. How many are wearing both?
> 	- 15 (J) + 10 (H) = 25
> 	- 25 - 20 = 5 <- $J \cap H$
> 2. Find $P(H|J)$.
> 	- = $\frac{5}{15}$
> 	- = $\frac{1}{3}$
> 3. Find $P(J|H)$.
> 	- = $\frac{5}{10}$
> 	- = $\frac{1}{2}$

> [!danger] Example 2
> This example has been voided as it is just practice of the [[L04 - Formal Notation For Conditional Probability#Formula|formula]] using a two-way table. Please refer to [OneNote](https://schoolsnsw-my.sharepoint.com/personal/alexis_kim3_det_nsw_edu_au/_layouts/15/Doc.aspx?sourcedoc=%7B1b95912f-87e8-4c02-9d27-f9d0c0905697%7D&action=view&wd=target%28_Class+Notes%2FCh8+Probability.one%7Ce7ba36f6-f374-ed49-bd14-1bd233c9de21%2FFor+my+Future+Forgetful+Self+%28FFFS%5C%29%7C0a8fa9a3-e210-9142-99d5-8ecca31f5515%2F%29&wdorigin=703&wdpartid=%7B6181a226-ef04-9844-8559-4ee9c49543e6%7D%7B1%7D&wdsectionfileid=1b32d6b0-f581-4212-b759-954d39ecea48) for the question.

> [!Example] Example 3
> In a group of *23 movie goers*, *13 bought popcorn*, *15 bought cola*, and *9 bought both*.
> 1. $P(P|C)$
> 	- $\frac{9}{15}$
> 	- $\frac{3}{5}$
> 2. $P(C|P)$
> 	- $\frac{9}{13}$
> 3. $P(C|M)$ ($= P(C)$)
> 	- $\frac{15}{23}$
> 	
> Two-way tables and venn diagrams are not required for this example, but can be very useful in terms of reasoning and proving the question.

