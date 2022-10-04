1. i. 

   **proof**: Denote set $G$ as the powerset of set $M$. We have $|G|=2^{|M|}$. This indicates if $M$ is infinite, $G$ is infinite. Take $g_i,g_j \in G, \forall g_i,g_j \in G$,  we have $g_i\Delta g_j =(g_i\cup g_j)-(g_i\cap  g_j)\in G$  .

   1) $g_i\Delta g_i =\empty$, every element in this group is its own inverse.  

   2) $g_i\Delta g_j =(g_i\cup g_j)-(g_i\cap g_j)=g_j \Delta g_i$ which is connectivity

   3) $(g_i\Delta g_j)\Delta g_k=((g_i\cup g_j)-(g_i\cap  g_j))\cup g_k - ((g_i\cup g_j)-(g_i\cap  g_j))\cap g_k= g_i\cup((g_j\cup g_k)-(g_j\cap g_k))-g_i\cap((g_j\cup g_k)-(g_j\cap g_k)) =g_i\Delta(g_j\Delta g_k)$ which is associative.

   4) The empty set is the identity of the group

   Thus $(P(M),\Delta)$ is abelian.$\square$

   ii.

   **proof**: 1) $((a,b)*(c,d))*(e,f)= (a,bd) *(e,f) = (a,bdf) = (a,b)*((c,d)*(e,f))$

   2) $(a,b) *(1,1)=(a,b)$, while $(1,1) * (a,b)=(1,b)$

   Thus $(\mathbb{R} \times \mathbb{R}, *)$ is non-abelian semigroup.

   The set of right- & left- units can be $\{(1,t),(k,t^{-1})|k,t\in\mathbb{R}\}$

2. $G=\{a^n=a, \forall n\geq 1\}$ 

3. $\because l_a, r_a$ are bijections. Assume that for any elements a,b in G, we can find x,y in G such that $a*x=b, y*a=b$.
   
   We are looking for a neutral element $e$. This satisfies $g_{0} e=g_{0}, g_{0} \in G .$ By assumption, there is some $e$ with $g e=g ,\forall g \in G .$ By assumption we may write $g=h g_{0}$ for some $h .$ Then, we have $g e=\left(h g_{0}\right) e=h\left(g_{0} e\right)=h g_{0}=g .$ and $\therefore g g^{-1}=e$ 
   
   $\therefore (G,*)$ is a group. $\square$

4. Let $T$ be the set of all $n \in \mathbb{N}_{>0}$ s.t.  $a_{f(1)} * \cdots * a_{f(n)}=a_{1} * \cdots * a_{n}$
   holds for all sequences $\left\langle a_{k}\right\rangle_{1 \leq k \leq n}$ of $n$ elements of $S$ which satisfy:$\forall i, j \in[1 \ldots n]: a_{i} * a_{j}=a_{j} * a_{i}$
   for every permutation $f: \mathbb{N}_{n} \rightarrow \mathbb{N}_{n}$.

   There are 3 cases to consider 
   1. $f(m+1) =m+1$. $a_{f(1)}*..a_{f(m+1)}=(a_{f(1)}*..a_{f(m)})*a_{f(m+1)} =(a_{1}*..a_{m})*a_{m+1}\xlongequal{\text{ind}}a_1*..a_{m+1} $

   2. $f(1)=m+1$. $a_{f(1)}*..a_{f(m+1)}=a_{f(1)}*(a_{f(2)}*..a_{f(m+1)})\xlongequal{\text{inc}}a_{m+1}*(a_{f^{\prime}(1)}*..a_{f^{\prime}(m)})\xlongequal{\text{def}}a_{m+1}*(a_1*...a_m)\xlongequal{\text{commutative}}(a_1*...a_m)*a_{m+1}=a_1*...a_m*a_{m+1}$. Here $f^{\prime}$ is defomed as $\forall k \in[1 \ldots m]: f^{\prime}(k)=f(k+1)$

   3. $f(r) = m+1$ for some $r\in[2..m]$. $a_{f(1)} \circ \cdots \cdot a_{f(m+1)}=\left(a_{f(1)} \circ \cdots \circ a_{f(r-1)}\right) \cdot\left(a_{f(r)} \circ\left(a_{f(r+1)} \circ \cdots \cdot a_{f(m+1)}\right)\right)$$=\left(a_{f^{\prime\prime}(1)} \circ \cdots \circ a_{f^{\prime\prime}(r-1)}\right) \circ\left(a_{f^{\prime\prime}(m+1)} \circ\left(a_{f^{\prime\prime}(r)} \circ \cdots \circ a_{f^{\prime\prime}(m)}\right)\right)$$=\left(a_{f^{\prime\prime}(1)} \circ \cdots \circ a_{f^{\prime\prime}(r-1)}\right) \circ\left(\left(a_{f^{\prime\prime}(r)} \circ \cdots \circ a_{f^{\prime\prime}(m)}\right) \circ a_{f^{\prime\prime}(m+1)}\right)$$=a_{f^{\prime\prime}(1)} \circ \cdots \cdot a_{f^{\prime\prime}(m+1)}$ Here $f^{\prime\prime}$ is defomed as $\forall k \in \mathbb{N}_{m+1}: \left\{\begin{array}{ll}\sigma(k) & : k \in[1 \ldots r-1] \\ \sigma(k+1) & : k \in[r \ldots m] \\ m+1 & : k=m+1\end{array}\right.$




5. i.

   **proof**: $\leftarrow$ if $(M,*)$ is a semigroup and $t$ has an inverse. We have $t^{-1} * b=t^{-1} t b=b, \quad b * t^{-1}=b t t^{-1}=b$. $\therefore$   $(\mathrm{M}, \odot)$ is a monoid.

   ​		   $\rightarrow$: Suppose $(\mathrm{M}, \odot)$ is a monoid, Suppose 1 is a monoid of $M$, and a is the monoid of $(M,*)$, we have $1=a * 1=a t 1=a t, \quad 1=1 * a=1 t a=t a$. Thus $a =t^{-1}$ which is the inverse of $(M,*)$. $\square$

   ii.

   **proof**: $\leftarrow:$ $(M,*)$ is a group, $\because a\odot b = atb$  we have  $a^\prime  (a\odot b)=  (b\odot a ) a^\prime, \forall a,b \in M$(1) ,$a^\prime$ is the one-dimention mapping from $M$ to $M$. And we have $\forall a,b,c \in G, a^\prime ac = c= b^\prime b c$.  From (1), we have $a^\prime   a = a^\prime  a  c  c^\prime = b^\prime  b  c^\prime =b^\prime b$. Let $a^\prime \odot a = e$ , then $e$ is the left monoid of $G$. $a^\prime $  Is the left inverse of $a$. $\therefore G$ is group.

   ​		    $\rightarrow$: The process of above prove is reversable. $\square$

