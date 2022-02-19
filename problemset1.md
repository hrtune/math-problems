# Problem Set 1

### Problem 1
Prove that $\log_4{6}$ is irrational.

Proof:\
I'm going to prove the proposition with contradiction.\
Suppose it can be expressed as a fraction $m/n$, where m and n are integers. Then,
$$ log_4{6} = {m \over n} $$
(use a definition of log)
$$ 4^{m / n} = 6 $$
iff
$$ 4^m = 6^n $$
iff
$$ 2^{2m} = 2^n3^n $$
iff
$$ 2^{2m-1} = 3^n $$

$2^k$ ($k=2m-1$) always produces an even number and $3^n$ always produces an odd number if $m$ and $n$ are integers. Because $m$ and $n$ are both integers, there is no such numbers satisfy the above equation.
By the contradiction, $log_4{6}$ is irrational. $\square$


### Problem 2
Use the Well Ordering Principle to prove that
$$ n \le 3^{n/3} $$ (1)


