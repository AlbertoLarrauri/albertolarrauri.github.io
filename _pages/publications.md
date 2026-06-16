---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<br>

---

<!--
#{% if author.googlescholar %}
#  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
#{% endif %}

#{% include base_path %}

#{% for post in site.publications reversed %}
#  {% include archive-single.html %}
#{% endfor %} 
-->


<h2> Peer-Reviewed Publications </h2>

<br>


<details>
<summary> 
<strong style="color:#52adc8"> Ineffectiveness for Search and Undecidability of PCSP Meta-Problems
</strong> <br>
Alberto Larrauri
<i> Symposium on Foundations of Computer Science </i>  (<strong> FOCS </strong>) 2025.
<a href="http://albertolarrauri.github.io/files/search.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
It is an open question whether the search and decision versions of promise CSPs are equivalent. 
Most known algorithms for PCSPs solve only their <i> decision </i> variant, and it is unknown whether they can be adapted to solve <i> search </i> as well. 
The main approaches, called BLP, AIP and BLP+AIP, handle a PCSP by finding a solution to a relaxation of some integer program. We prove that rounding those solutions to a proper search certificate can be as hard as any problem in the class TFNP. In other words, these algorithms are ineffective for search. Building on the algebraic approach to PCSPs, we find sufficient conditions that imply ineffectiveness for search. Our tools are tailored to algorithms that are characterized by minions in a suitable way, and can also be used to prove undecidability results for meta-problems. This way, we show that the families of templates solvable via BLP, AIP, and BLP+AIP are undecidable. <br>



Using the same techniques we also analyze several algebraic conditions that are known to guarantee the tractability of finite-template CSPs. We prove that several meta-problems related to cyclic polymorphims and WNUs are undecidable for PCSPs. In particular, there is no algorithm deciding whether a finite PCSP template (1) admits cyclic a polymorphism, (2) admits a WNU. 

<br>
</div>
</details>

---

<details>
<summary> 
<strong style="color:#52adc8"> Equations over Finite Monoids with Infinite Promises
</strong> <br>
Alberto Larrauri, Antoine Mottet, Standa Živný
<i> ACM Transactions on Computational Logic </i> 2026.
<a href="http://albertolarrauri.github.io/files/infinite_promises.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
Recent work has established a complete complexity
  classification of the problem of solving a system of equations over a 
  monoid \( N\) assuming that a solution exists over a monoid
  \( M \), where both monoids are finite and \( M \) admits a homomorphism to
  \( N \). Using the algebraic approach to promise constraint satisfaction
  problems, we extend this complexity classification in two directions: we allow arbitrary relations to be added to the monoids, and we moreover allow the monoid \( M\) to be finitely generated instead of finite.
<br>
</div>
</details>

---

<details>
<summary> 
<strong style="color:#52adc8"> Optimal Inapproximability of Promise Equations
over Finite Groups
</strong> <br>
Silvia Butti, Alberto Larrauri, Standa Živný
<i> The International Colloquium on Automata, Languages and Programming  </i>  (<strong> ICALP track A </strong>) 2025.
<a href="http://albertolarrauri.github.io/files/promise_inapproximability.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
A celebrated result of Håstad established that, for any constant  \(\varepsilon>0 \),
it is NP-hard to find an assignment satisfying a  \((1/|G|+\varepsilon) \)-fraction
of the constraints of a given  \(3 \)-Lin instance over an Abelian group  \(G \) even if
one is promised that an assignment satisfying a  \((1-\varepsilon) \)-fraction of
the constraints exists. Engebretsen, Holmerin, and Russell showed the same
result for  \(3 \)-Lin instances over any finite (not necessarily Abelian) group.
In other words, for almost-satisfiable instances of  \(3 \)-Lin the random
assignment achieves an optimal approximation guarantee. <br>



We prove that the random assignment algorithm is still best possible under a stronger
promise that the  \(3 \)-Lin instance is almost satisfiable over an arbitrarily
more restrictive group.
<br>
</div>
</details>

---

<details>
<summary> 
<strong style="color:#52adc8"> Solving Promise Equations Over Monoids and Groups
</strong> <br>
Alberto Larrauri, Standa Živný
<i> The International Colloquium on Automata, Languages and Programming </i> (<strong> ICALP track B </strong>) 2024, and <i> ACM Transactions on Computational Logic </i> 2024.
<a href="http://albertolarrauri.github.io/files/PromiseEquations.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
We give a complete complexity classification for the problem of finding a solution to a given system of equations over a fixed finite monoid, given that a solution over a more restricted monoid exists. As a corollary, we obtain a complexity classification for the same problem over groups. 
<br>
</div>
</details>


---



<details>
<summary> 
<strong style="color:#52adc8"> Synthesis of Controllers for Continuous Blackbox Systems
</strong> <br>
Benedikt Maderbacher, Felix Windisch, Alberto Larrauri, Roderick Bloem
<i> Verification, Model Checking, and Abstract Interpretation </i> (<strong> VMCAI </strong>) 2025,
[DOI](https://doi.org/10.1007/978-3-031-82703-7_7)
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
Feed-forward controllers compute control outputs to adapt to changes in environmental parameters in a cyber-physical system. When synthesizing control functions it can be difficult to give an analytical description of the controlled plant or to decide the expected control output ahead of time. These systems must, however, adhere to strict safety requirements, which makes it hard to write correct controllers. In this paper, we propose a novel blackbox synthesis approach to construct a continuous control function while dynamically sampling a limited number of test cases. The controller is guaranteed to be correct for a given Lipschitz bound. It can be adapted to work for increasingly conservative estimates of the bound based on observed behavior, iteratively providing increasing confidence in its correctness. Our algorithm employs a linear interpolation model, based on a Delaunay triangulation, to identify candidate control functions. It then generates additional test cases to either confirm a candidate or to improve the model. We evaluate our approach on random benchmarks and CPS examples to show its effectiveness.
<br>
</div>
</details>


---


<details>
<summary> 
<strong style="color:#52adc8"> Limiting Probabilities of First Order Properties of
Random Sparse Graphs and Hypergraphs
</strong> <br>
Alberto Larrauri, Tobias Müller & Marc Noy, 
<i> Random Structures and Algorithms</i> (<strong> RSA </strong>) 2022.
<a href="http://albertolarrauri.github.io/files/limits_binomial_graphs.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
We study the set  \(L_c \) of limiting probabilities of first order sentences in the binomial random graph  \(G(n, p) \) in the sparse regime  \(p \sim c/n \). We show there is a critical value  \(c_0 \) for which  \(L_c \) is dense in  \([0,1] \) if and only if  \(c \geq c_0 \). Moreover, the closure of  \(L_c \) is always a finite union of closed intervals. The value  \(c_0 \) is precisely the one witnessing  \(\mathrm{Pr}(G(n, c_0/n) \text{ is acyclic }) = 1/2 + o(1) \). These results are also extended to the binomial  \(d \)-uniform hypergraph. 
<br>
</div>
</details>

---





<details>
<summary> 
<strong style="color:#52adc8"> Industry Paper: Surrogate Models for Testing Analog Designs
under Limited Budget – a Bandgap Case Study
</strong> <br>
Roderick Bloem, Alberto Larrauri, Roland Lengfeldner, Cristinel Mateis, Dejan Ničković & Björn Ziegler
<i> Emebedded Systems Week </i> (<strong> ESWEEK </strong>) 2022.
<a href="http://albertolarrauri.github.io/files/bayesian_testing.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>

Testing analog integrated circuit (IC) designs is notoriously hard. 
Simulating tens of milliseconds from an accurate transistor level model 
of a complex analog design can take up to two weeks of computation. 
Therefore, the number of tests that can be executed during the late 
development stage of an analog IC can be very limited. We leverage the 
recent advancements in machine learning (ML) and propose two techniques, 
artificial neural networks (ANN) and Gaussian processes,
to learn a surrogate model from an existing test suite. We then explore 
the surrogate model with Bayesian optimization to guide the generation of additional tests. 
We use an industrial bandgap case study to evaluate the two approaches 
and demonstrate the virtue of Bayesian optimization in efficiently 
generating complementary tests with constrained effort.

<br>
</div>
</details>



---

<details>
<summary> 
<strong style="color:#52adc8"> Probabilities of First Order Sentences on Sparse Random Relational Structures: An Application to Definability on Random CNF Formulas
</strong> <br>
Alberto Larrauri,
<i> Journal of Logic and Computation</i> (<strong> JLC </strong>) 2021.
<a href="http://albertolarrauri.github.io/files/random_structures_cnf.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
We show a convergence law for first order logic in a general model of relational structures. In this model, the probability of a sentence varies smoothly with the density of each predicate. A consequence of this result is that, asymptotically, no certificate for unsatisfiability definable in FO logic succeeds with positive probability on random CNF formulas with linear number of clauses. 

<br>
</div>
</details>





---



<h2> Preprints and Articles in Preparation</h2>



<br>



<details>
<summary> 
<strong style="color:#52adc8"> Limiting Probabilities of First Order Properties of
Sparse Graphs with Given Degree Sequences
</strong> <br>
Alberto Larrauri, Guillem Perarnau, 
<i> under submission </i> 
<a href="http://albertolarrauri.github.io/files/Degree_Sequences.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
We study the set  \(L \) of limiting probabilities of first order sentences in the random graph  \(G_n \) with given degree sequence in the sparse regime. Similarly to previous work on the binomial random graph  \(G(n, c/n) \), we show that the closure of  \(L \) is always a finite union of intervals. Moreover, whether  \( L \) is dense in  \([0,1] \) depends only  \(\rho \), the ratio between the first and second moment of the limiting degree distribution, which also determines the appearance of a giant component in this random graph. We prove that  \( L \) is dense in  \( [0,1] \) if and only if 
\( \rho\geq \rho_0 \), where  \( \rho_0 \) is the critical value witnessing  \(\mathrm{Pr}(G_n \text{ is acyclic }) = 1/2 + o(1) \).
<br>
</div>
</details>

---
<details>
<summary> 
<strong style="color:#52adc8"> Minimization and Synthesis in Sequential Compositions of Mealy Machines: Revisited
</strong> <br>
Alberto Larrauri & Roderick Bloem, 
<i> in preparation </i> 
<a href="http://albertolarrauri.github.io/files/minimization_synthesis.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>

We study two problems on systems that consist of a sequential composition of Mealy machines, called head and tail. In the first problem, the goal is to obtain a smallest replacement for either component without altering the external behavior of the system. We show that minimization of the head and the tail are both NP-complete. However, existing methods proposed for the minimization of the tail have doubly-exponential complexity. The source of this complexity blow-up is identified and an alternative algorithm is proposed. In the second problem, only one component - either the head or the tail - is known, and a desired model for the whole system is given. The goal now is to build the missing component. We show that it takes polynomial time to decide whether a missing tail can be built, but an appropriate model may be of exponential size.
<br>
</div>
</details>

---


<details>
<summary> 
<strong style="color:#52adc8"> Conformance Testing of Mealy Machines Under
Input Restrictions
</strong> <br>
Alberto Larrauri & Roderick Bloem, 
<i> in preparation </i> 
<a href="http://albertolarrauri.github.io/files/conformance_testing.pdf
">
<img src="./../images/pdf-svg.svg" width=16em title="pdf"/>
</a>
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>

We introduce a grey-box conformance testing method for networks of interconnected Mealy Machines. This approach addresses the scenario where all interfaces of the component under test are observable, but its inputs are under the control of other white-box components. We prove new conditions for full fault detection that exploit repetitions across branching executions of the composite machine in a novel way. Experimental evaluation of our approach on cascade compositions of up to a thousand states is provided, showing that it notably outperforms existing black-box testing techniques.
<br>
</div>
</details>



---


<details>
<summary> 
<strong style="color:#52adc8"> Preservation Theorems on Random Graphs 
</strong> <br>
Alberto Larrauri,
<i> in preparation</i>.
</summary>
<br>
<div style="margin-left: 2em">
<strong> Summary: </strong>
Preservation theorems are results in classical model theory relating semantic classes of first order sentences to syntactic ones. We focus on Lyndon's theorem and Łoś–Tarski's theorem. The first states that a sentence which is monotone in some predicate is equivalent to a sentence which is positive in that predicate, and the second that a sentence closed under embeddings is equivalent to a purely existential one. Famously, both theorems fail when we restrict them to finite structures. This is the case even for finite graphs. We consider probabilistic versions of those theorems on random structures, where equivalence between sentences is substituted for "asymptotically-almost-sure" equivalence. We show that the probabilistic Lyndom theorem holds in multiple regimes of  \(G(n,p) \) including  \(p \sim c n^\alpha \) for  
\(\alpha=-1 \), or  \(\alpha= - (k+1)/k \), and close to the connectivity threshold  \(p \sim c/n + d\log n/n \). Similarly, we also prove the probabilistic Łoś–Tarski's theorem holds for those regimes of 
\(G(n,p) \) as well as in the  \(n \)-vertex uniform random graph chosen from an arbitrary addable minor-closed family. 
<br>
</div>
</details>

---

