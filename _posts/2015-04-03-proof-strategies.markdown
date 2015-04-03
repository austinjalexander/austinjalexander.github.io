---
layout: post
title:  "Proof Strategies"
date:   2015-04-03 17:30:00
categories: 
---
[UNDER CONSTRUCTION]

Daniel J. Velleman's popular handbook [1] on proving technique's is simply fantastic. 
Below I offer some snippets.

#### Definitions

* **hypothesis:** the antecedent (_if_ component) of a conditional statement; in this context, hypotheses (also called premises) are treated as assumptions
* **conclusion:** the consequent (_then_ component) of a conditional statement; in this context, conclusions are the elements, which, if proven false, render the statement under consideration incorrect
* **theorem:** a statement that says if certain hypotheses are true, then some conclusion must also be true (and, thus, the statement has been proven)

#### Symbols

* $$P,Q,...$$ **statements:** as individual letters, each is used as a shorthand to represent a given statement (also known as a _proposition_ or a _operand_), which, known or unknown, may be TRUE or FALSE (e.g., let $$P$$ stand for $$2 + 2 = 4$$; $$P$$, in this case, is TRUE)
* $$\neg$$ **negation/complement:** the _NOT_ truth function, a unary connective, also known as an _operator_, that returns the inverted truth value of the connected statement; for example, if $$P$$ is TRUE, $$\neg P$$ is FALSE
* $$\vee$$ **inclusive disjunction:** the _OR_ truth function, is a binary connective that returns the value TRUE if at least one of the connected statements is TRUE
* $$\wedge$$ **conjunction:** the _AND_ truth function, is a binary connective that returns the value TRUE if both connected statements are TRUE

#### Truth Tables (T = TRUE, F = FALSE)

<table class="table table-bordered table-condensed text-center" style="width:300px">
  <thead>
    <tr>
      <td>$$P$$</td>
      <td>$$Q$$</td>
      <td>$$\neg P$$</td>
      <td>$$\neg Q$$</td>
      <td>$$P \vee Q$$</td>
      <td>$$P \wedge Q$$</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>T</td><td>T</td><td>F</td><td>F</td><td>T</td><td>T</td>
    </tr>
    <tr>
      <td>T</td><td>F</td><td>F</td><td>T</td><td>T</td><td>F</td>
    </tr>
    <tr>
      <td>F</td><td>T</td><td>T</td><td>F</td><td>T</td><td>F</td>
    </tr>
    <tr>
      <td>F</td><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td>
    </tr>
  </tbody>
</table>

#### Format
A logical argument may take the form:

$$
\begin{array}{}
  P \vee Q \\
  \neg Q \\
  \hline 
  \therefore P
\end{array}
$$

Let $$P$$ stand for the statement $$(3 < \pi)$$.  
Let $$Q$$ stand for the statement $$(3 = \pi)$$.  

Then $$P \vee Q$$ stands for $$(3 \leq \pi)$$.  
Then $$\neg Q$$ means $$(3 \neq \pi)$$.

Assuming $$P \vee Q$$.  
Given $$\neg Q$$.  

Therefore, $$P$$.




To prove a conclusion of the form $$P \rightarrow Q$$, assume $$P$$ is TRUE and then prove $$Q$$. If $$P$$ is assumed, it may then be used as any other hypothesis. 

---

REFERENCES

[1] D. Velleman, _How to Prove It: A Structured Approach_. Cambridge: Cambridge University Press, 2006.  
