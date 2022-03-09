<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>
<script type="text/x-mathjax-config">
 MathJax.Hub.Config({
 tex2jax: {
 inlineMath: [['$', '$'] ],
 displayMath: [ ['$$','$$'], ["\\[","\\]"] ]
 }
 });
</script>

# Problem Set 4

https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/assignments/MIT6_042JS15_ps4.pdf

### Problem 1

Suppose $(m,n)$ shows the current position of the robot.
And the defined transitions of the robot are:
$$ \{(m, n) \rightarrow (m \pm 1, n \pm 3) | m,n \in \Z\} $$(1)
$$ \{(m, n) \rightarrow (m \pm 2, n \mp 1) | m,n \in \Z\} $$(2)


**Lemma 4.1.1** The preserved invariant of the state machine is
$$ \{(a-b, 3a+2b) | a,b \in \Z\} $$(3)

Base case: for the initial state,
$$a-b = 0\ AND\ 3a+2b = 0$$
iff  $a = 0$ and $b = 0$ so (3) holds for the base case.

Inductive step: suppose (3) holds for $(m, n)$. So,
* $a-b = m$
* $3a+2b = n$
iff
$$ a = \frac{2m+n}{4} , b = \frac{-3m+n}{5} $$ (4)

The next step will be (1) or (2). For (1),
$$ a = 



