# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$


## Answer
Using the definition from the slides, Big-O is defined as T (n) ∈ O(f (n)) if there are positive constants c and n0 such that T (n) ≤ cf (n)
for all n ≥ n0

Since o(g(n)) must be true for all positive constants and since O(g(n)) only needs a single constant c. If Little-o is true, then Big-O, which must only check one value c against the same function, must be true as well.

The other difference is that little-o f(n) < c g(n) where Big-o f(n) ≤ g(n). This means that little o MUST grow slower than cg(n), big o can grow slower or at the same rate as cg(n). Therefore, the smallest Big-O growth rate is smaller than the smallest little-o growth rate.

## Sources and Plagarism Statement
Used only the in class slides for the defintion of Big-O, nothing else.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
