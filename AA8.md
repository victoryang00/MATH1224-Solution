Answer sheet 9 - Yiwei Yang 2018533218
## 1
### i 
We first have that $I,F$ is the ultra filter, so we have 2 scenarios $N\subset U,N\in F$ or $M/\ N\in F$. (every set is either large or co-large)

$\rightarrow F$ is ultrafiler, so that there exists $N\subset U$ such taht $N\notin F$ $M/\N\notin F$. Since $F\neq \empty$ So for $G\in F$, we have $G\subset N\text{ or }M$ or both empty.

we have $\empty \notin F$ So there;s no $H_1,H_2 \in F$ $H_1\subset N \text{ or }M/\ N$ Suppose the latter, let $B=\{N\cap H|H\in F\},$ so that $\empty \in A$. But $F^{\prime}=F\cup B\cup\{N\}$ does not contain $\empty$ and $F \subset F^{\prime}$ which is contradiction. So $\square$
 
 
$\leftarrow$ $(M/\ N)\cap N=\empty$ and $F^{\prime}$ does not exists. So $F$ is ultra filter. 
### ii
Let $\mathcal{F}=\{N\subset M|m_0\in N\}$. We have $\forall N\in F,m_{0} \in N$, so $\empty \notin F^{\prime}$

let $N_1,N_2\in F,m_0\in (N_1\cap N_2)$ we have $(N_1\cap N_2)\in F$ so $F$ is a filter. and for $H\in P(U)/\ F, \{m_0\}\in F, H\cup \{m_0\}=\empty$ so   

### iii
 Take $X$ to be any infinite set, choose $\mathrm{N}$ a countable subset of $X$ and enumerate $N$ as a sequence, $N=\left\{x_{n}\right\}_{n \in \mathcal{N}} .$ Set $B_{1}=N$ and $B_{n}=N /\left\{x_{1}, \ldots, x_{n-1}\right\}, n \in \mathcal{N}$
Then $\mathcal{B}=\left\{B_{n}: n \in \mathcal{N}\right\}$ is a filter base that can be extended to a non principal ultrafilter on $\mathrm{X}$.$F \subset F^{\prime}$. $F$ is ultrafilter.
### iv
 Let $R=\mathcal{F}(I, \mathbb{R})$ and let $U=\left\{f^{-1}(0): f \in J\right\}$. First, note that if $f \in J$, then we can multiply $f$ by a function to assume $f$ only takes the values 0 and 1 without changing its zero set (just multiply by a function that is $1 / f$ when $f$ doesn't vanish). So, $A \in U$ iff the function $1_{I \backslash A}$ which is 1 on $I \backslash A$ and 0 on $A$ is in $J$.
We now see easily that $U$ is a filter: it is closed under supersets since $J$ is closed under multiplication by elements of $R$, and it is closed under intersections since $1_{I \backslash A}+1_{I \backslash B}$ vanishes only on $A \cap B$. To see that it is an ultrafilter, it suffices to show that for any $A \subseteq I$, exactly one of $e=1_{A}$ and $f=1_{I \backslash A}$ is in $J$. This follows from the fact that $e+f=1$ and $e f=0$ : since $e+f=1$, they cannot both be in $J$, and since $e f=0$, at least one must be in $J$ since $J$ is prime.

## 2 
Since $R$ has no zero-divisor. The closure under the calculation is trivial, and the associativity under plus and mul is satisfied.

For $(\mathbb{Q}(\mathbb{R}),+)$ we have $[(O_R,I_R)]$ is the unit and $\forall (r,s)\in \mathbb{Q}(\mathbb{R}),$ $(-r, s)+(r, s):=(-rs+rs, ss)=$$(O_R,SS)=(O_R,I_R)$, which is invertible.

Also, for $\forall (r_i,s_i)\in\mathbb{Q}(\mathbb{R}), i\in\{1,2,3\}$ we have $(r_3,s_3)((r_1,s_1)+(r_2,s_2))=(r_3,s_3)(r_1s_2+r_2s_1,s_1s_2)$ $=(r_3(r_1s_2+s_1r_2),s_1s_2s_3)=(r_1r_2,s_3s_1)+(r_3r_2,s_3s_2)=(r_3,s_3)(r_1,s_1)+(r_3,s_3)(r_2,s_2)$ the distribution holds, too.

So, it's a ring and the commutativity of $\mathbb{Q}(\mathbb{R}),\cdot$ is deducted from $(R,\cdot)$ .

To prove that $(O_R,I_R)$ is not invertible, $\forall (r_1,s_1),(r_2,s_2)\neq(O_R,I_R)$ we have $(r_1,s_1)\cdot (r_2,s_2)=(r_1r_2,s_1s_2)=(O_R,I_R)$. $r_1r_2=O_R$. so that $r_1=O_R \ r_2=O_R$.

$\mathbb{Q}(\mathbb{R})$ has no zero-divisor, we have $(I_R,I_R)$ is unit and $(O_R,I_R)$ is not invertible. Thus $(\mathbb{Q}(\mathbb{R}),+,\cdot)$ is a field.

## 3
### i
The closure of $+,\cdot$ is trivial. 

As for associativity, in $(R_W,+)$, it follows directly from the associativity of + in R and W. Now $\forall(r_i,w_i)\in R_W$  $(r_3,w_3)*((r_1,w_1)*(r_2,w_2))=(r_1r_2r_3,r_3(r_1w_2+r_2w_1)+r_1r_2w_3)=((r_1,w_1)+(r_2,w_2))*(r_3,w_3)$ and $(O,O_W),(I,O_W)$ are respectively units for + and *.
$\forall (r,w)\in R_W$ $(r,w)+(-r,-w)= (O,O_w)$, so every element's invertible.

commutativity is from (R,+) (W,+)

The distribution is $\forall (r_1,w_1)(r_2,w_2)(r_3,w_3)\in R_W$, we ahve   $(r_3,w_3)*((r_1,w_1)+(r_2,w_2))=$$(r_3,w_3)(r_1w_2+r_2w_1,w_1w_2)$ $=(r_3(r_1w_2+w_1r_2),w_1w_2w_3)$$=(r_1r_2,w_3w_1)+(r_3r_2,w_3w_2)=$$((r_1,w_1)+$$(r_2,$$w_2))$$*(r_3,w_3)$

Thus, because $(O,O_w)\neq(I,I_W).$ $(R_W,+,*)$ is a non-zero communitative unitary ring.

### ii
The $R_W$'s maximal ideal is $m\leftrightarrow d(R_W)\geq \text{dim } R_W \leftrightarrow R_W\text{ is finite demensional. } W$ is finite dimensional as R-vector space. d is depth, h is height

Suppose the maximal prime is $m$, deduction proof on $d(R_W)$

$d(R_W)=0$ $\forall$ big enough $n$ $l(R_W/m^n)$ is constant. So that there exist $m^{n+1}=m^{n}$ so that $m^{n}=0$ So that dim $R_W$=0

If $d(A)>0$. let $p_0\subset p_1\ \cdots p_r$ be $R_W$'s prime ideal chain. let $x\in p_1/\ p_0$, $\pi$ is the homomorphism from $R_W$ to $R_W^{\prime}=R_W/\ p_0$. So $x^{\prime}=\pi(x)\neq 0$ $R_W^{\prime}$ is integer ring. So that $d(R_W^{\prime} /\ \text<x\prime\text>)\leq d(R_W^{\prime})-1$ if $m^{\prime}$ is the maximal ideal, $R_W^{\prime}/\ m^{\prime n}$ is the homomorphism image of $R_W/\ m^{n}$. So $l(R_W/\ m)^{n}\geq l(R_W^{\prime}/\ m^{\prime n})$ So that $d(R_W)\geq d(R_W^\prime)$ and $d(R_W^{\prime} /\ \text<x\prime\text>)\leq d(R_W)-1$.

So that the length of $d(R_W^{\prime} /\ \text<x\prime\text>)$ is no bigger than $d(R_W)-1$, but p1...pr construct a chain of length $r-1$. So that dim $R_W\leq d(R_W)$
## 4
Let height $p$ be the sup of the length r of prime ideal chain $p_0\subset p_1\ \cdots p_r=p$ whose destination is $p$ and depth $p$ be the sup of the length s of prime ideal chain $p=p_0\subset p_1\ \cdots p_s$ who starts with $p$

We have height $p$ = dim $R_p$, depth $p$ = dim $R/\ p$ because $S^{-1}p_0\subset S^{-1}p_1\cdots S^{-1}p_r=S^{-1}p, S=R/\ p$ and $p/\ p= q_o/\ p\subset q_1/\ p... q_s/\ p$ are the prime ideal chain of $S^{-1} R$ and $R /\ p$

For $a$ as maximal prime of d-dim commutative non-zero unitary ring $R$, for all $p_i$ , we have $0\leq$ height $p_i\leq$ height $a=$ dim $R$. $\forall t,0 \leq t\leq d$ exists prime ideal $p_i$ such that height $p_i=t$ height $p_i=d$ if and only if $p_i=a$

Because $p_0\subset \cdots p_r=p\subset a$ and $R$ have prime ideal chain $p_0\subset \cdots p_{dim(R)}$