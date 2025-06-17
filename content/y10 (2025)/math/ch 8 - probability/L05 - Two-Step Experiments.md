---
tags:
  - Academics/Math
lesson: 5
math-topic: Topic 3 - Probability (Chapter 8, Y10)
math-type: Core
date: 2025-06-17
---
# Two-Step Experiments
## Information
- A two-step experiment can be visualised using a **tree diagram**. You can find an example on [OneNote](https://schoolsnsw-my.sharepoint.com/personal/alexis_kim3_det_nsw_edu_au/_layouts/15/Doc.aspx?sourcedoc=%7B1b95912f-87e8-4c02-9d27-f9d0c0905697%7D&action=view&wd=target%28_Class+Notes%2FCh8+Probability.one%7Ce7ba36f6-f374-ed49-bd14-1bd233c9de21%2FFor+my+Future+Forgetful+Self+%28FFFS%5C%29%7C0bbac7e8-8c38-c047-8003-a5fcf8198802%2F%29&wdorigin=703&wdpartid=%7B209cc0fa-e59c-4747-b561-b4fd7bfce1fe%7D%7B1%7D&wdsectionfileid=1b32d6b0-f581-4212-b759-954d39ecea48).
- In a tree diagram, it starts from "Start" and each step is a column of outcomes.
- The sample space is composed of the combined probabilities of each result.
	- For example, in an experiment that flips two coins, $P(H, H) = \frac{1}{2} \times \frac{1}{2} = \frac{1}{4}$
### With Replacement
- Two-step experiments can have outcomes that can be replaced.
- This means that an outcome can be repeated.
- The probability of the outcomes will also stay the same.

> [!Example] KICK (With Replacement)
> The letters are chosen from the word **KICK**. 
> - (A tree diagram can be found on [OneNote](https://schoolsnsw-my.sharepoint.com/personal/alexis_kim3_det_nsw_edu_au/_layouts/15/Doc.aspx?sourcedoc=%7B1b95912f-87e8-4c02-9d27-f9d0c0905697%7D&action=view&wd=target%28_Class+Notes%2FCh8+Probability.one%7Ce7ba36f6-f374-ed49-bd14-1bd233c9de21%2FFor+my+Future+Forgetful+Self+%28FFFS%5C%29%7C0bbac7e8-8c38-c047-8003-a5fcf8198802%2F%29&wdorigin=703&wdpartid=%7B209cc0fa-e59c-4747-b561-b4fd7bfce1fe%7D%7B1%7D&wdsectionfileid=1b32d6b0-f581-4212-b759-954d39ecea48).)
> - In a scenario where the experiment is with replacement, the probabilities will not change.
> - The sample space will be {KK, KI, KC, IK, II, IC, CK, CI, CC}.
> 	- The probability of K is $\frac{2}{4}$.
> 	- The probability of I is $\frac{1}{4}$.
> 	- The probability of C is $\frac{1}{4}$.
> - Here's a few probability questions based on this experiment.
> 	1. $P(\fbox{K then C}) = \frac{2}{4} \times \frac{1}{4} = \frac{1}{8}$
> 	2. $P(\fbox{a K and a C}) = P(K, C) + P(C, K)$
> 		- $\frac{2}{4} \times \frac{1}{4} + \frac{1}{4} \times \frac{2}{4} = \frac{1}{4}$
> 	3. $P(\fbox{K, K | at least one K (given)}) = \frac{n(K ,K)}{n(\fbox{at least one K})} = \frac{\frac{1}{4}}{\frac{3}{4}}= \frac{1}{3}$
### Without Replacement
- Two step experiments can have outcomes that *cannot* be replaced.
- This means that an outcome cannot be repeated.
- The probability of outcomes will change depending on the remaining outcomes.

> [!Example] KICK (Without Replacement)
> The letters are chosen from the word **KICK**. 
> - (A tree diagram can be found on [OneNote](https://schoolsnsw-my.sharepoint.com/personal/alexis_kim3_det_nsw_edu_au/_layouts/15/Doc.aspx?sourcedoc=%7B1b95912f-87e8-4c02-9d27-f9d0c0905697%7D&action=view&wd=target%28_Class+Notes%2FCh8+Probability.one%7Ce7ba36f6-f374-ed49-bd14-1bd233c9de21%2FFor+my+Future+Forgetful+Self+%28FFFS%5C%29%7C0bbac7e8-8c38-c047-8003-a5fcf8198802%2F%29&wdorigin=703&wdpartid=%7B209cc0fa-e59c-4747-b561-b4fd7bfce1fe%7D%7B1%7D&wdsectionfileid=1b32d6b0-f581-4212-b759-954d39ecea48).)
> - In a scenario where the experiment is with replacement, the probabilities will not change.
> - The sample space will be {KK, KI, KC, IK, II, IC, CK, CI, CC}.
> 	- In the first step, the outcomes of K, I, C are the same as the example [[#With Replacement]].
> 	- In the second step, the outcomes of K, I, and C are reduced.
> 		- If the outcome of the first step was K ...
> 			- The probability of K is now $\frac{1}{3}$.
> 			- The probability of I is now $\frac{1}{3}$.
> 			- The probability of C is now $\frac{1}{3}$.
> 		- If the outcome of the first step was I ...
> 			- The probability of K is now $\frac{2}{3}$.
> 			- The probability of C is now $\frac{1}{3}$.
> 		- If the outcome of the first step was C ...
> 			- The probability of K is now $\frac{2}{3}$.
> 			- The probability of I is now $\frac{1}{3}$.
> 	- To find the probability of the results, you must combine the outcomes of the two steps. Refer to the initial [[#Information|information]].
> - Here's a few probability questions based on this experiment.
> 	1. $P(\fbox{K then C}) = \frac{1}{6}$
> 	2. $P(\fbox{a K and a C}) = \frac{1}{6} + \frac{1}{6} = \frac{1}{3}$
> 	3. $P(\fbox{KK | at least one K}) = \frac{P(K,K)}{P(\fbox{at least one K})} = \frac{\frac{1}{6}}{\frac{5}{6}} = \frac{1}{5}$
> 		- To get $\frac{5}{6}$, you combine the outcomes of KK, KI, KC, IK, and CK.
