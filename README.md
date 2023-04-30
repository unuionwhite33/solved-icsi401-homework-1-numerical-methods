Download Link: https://assignmentchef.com/product/solved-icsi401-homework-1-numerical-methods
<br>
<h1>1.1        Calculus, Taylor series</h1>

Consider the function.

<ol>

 <li>Compute lim<em><sub>x</sub></em><sub>→0 </sub><em>f</em>(<em>x</em>) using l’Hˆopital’s rule.</li>

 <li>Use Taylor’s remainder theorem to get the same result:

  <ul>

   <li>Write down <em>P</em><sub>1</sub>(<em>x</em>), the first-order Taylor polynomial for sin(<em>x</em>) centered at <em>a </em>= 0.</li>

   <li>Write down a good upper bound on the absolute value of the remainder <em>R</em><sub>1</sub>(<em>x</em>) = sin(<em>x</em>)− <em>P</em><sub>1</sub>(<em>x</em>), using your knowledge about the derivatives of sin(<em>x</em>). The goal here is to show that <em>R</em><sub>1</sub>(<em>x</em>)<em>/x </em>is negligible.</li>

   <li>Express, and compute the limits of the two terms as <em>x </em>→ 0. <strong>2 Asymptotic notation</strong></li>

  </ul></li>

</ol>

Recall the definitions of the asymptotic notations. We will say that <em>f</em>(<em>x</em>) has “order of growth <em>x<sup>α </sup></em>as <em>x </em>→ <em>x</em><sub>0</sub>” (where <em>x</em><sub>0 </sub>is either some fixed real number or ±∞) if <em>f</em>(<em>x</em>) = Θ(<em>x<sup>α</sup></em>) as <em>x </em>→ <em>x</em><sub>0</sub>.

<ol>

 <li>Consider the functions <em>f</em>(<em>x</em>) = <em>x</em>sin<em>x </em>and <em>g</em>(<em>x</em>) = <em>x</em>. Is <em>f</em>(<em>x</em>) = Θ(<em>g</em>(<em>x</em>)) as <em>x </em>→ ∞? Why or why not? (Hint: As always, you should refer back carefully to the definition of Θ(·).)</li>

 <li>Suppose that we know that <em>f</em>(<em>x</em>) = <em>x </em>+ Θ(<em>x</em><sup>2</sup>) and <em>g</em>(<em>x</em>) = Θ(<em>x</em>) <em>&gt; </em>0 as <em>x </em>→ 0. Determine the order of growth of <em>f</em>(<em>x</em>) + <em>g</em>(<em>x</em>).</li>

</ol>

(This problem is meant to get you comfortable with manipulating asymptotic notation when it appears in expressions. When I say something like “<em>f</em>(<em>x</em>) = <em>x </em>+ Θ(<em>x</em><sup>2</sup>)”, this means that there is some function <em>h</em>(<em>x</em>) = Θ(<em>x</em><sup>2</sup>), and <em>f</em>(<em>x</em>) = <em>x</em>+<em>h</em>(<em>x</em>). That is, the fact that <em>h</em>(<em>x</em>) = Θ(<em>x</em><sup>2</sup>) is the <em>only </em>thing you know about <em>h</em>(<em>x</em>).)

<ol start="3">

 <li>Suppose that we know that <em>f</em>(<em>x</em>) = <em>e</em><sup>Θ(<em>x</em>) </sup>as <em>x </em>→ ∞. Does this imply that <em>f</em>(<em>x</em>) = Θ(<em>e<sup>x</sup></em>)? (Hint: Think carefully about the definition of Θ(·), and consider <em>f</em>(<em>x</em>) = <em>e</em><sup>2<em>x</em></sup>.)</li>

</ol>

1-1

1-2                                                  Homework 01: ICSI 401 – Numerical Methods

<h1>1.3        Relative versus absolute error</h1>

<ol>

 <li>Suppose that you are approximating a function <em>g</em>(<em>n</em>) by some function <em>f</em>(<em>n</em>). Suppose, further, that you know that the absolute error in approximating <em>g</em>(<em>n</em>) by <em>f</em>(<em>n</em>) satisfies |<em>f</em>(<em>n</em>)−<em>g</em>(<em>n</em>)| = <em>o</em>(1) as <em>n </em>→ ∞ (that is, lim<em><sub>n</sub></em><sub>→∞ </sub>|<em>f</em>(<em>n</em>) − <em>g</em>(<em>n</em>)| = 0). Is it true that the <em>relative </em>error also decays to 0? If not, come up with functions <em>f</em>(<em>n</em>) and <em>g</em>(<em>n</em>) for which this is not true. (Hint: Come up with some <em>g</em>(<em>n</em>) and <em>f</em>(<em>n</em>) satisfying <em>g</em>(<em>n</em>) = <em>o</em>(1) and <em>f</em>(<em>n</em>)<em>/g</em>(<em>n</em>) = Θ(1).)</li>

</ol>

<h1>1.4         Matlab warmup/Gentle linear algebra review</h1>

<ol>

 <li>Complete G&amp;C Chapter 2, Exercise 2.</li>

 <li>Complete G&amp;C Chapter 2, Exercise 3.</li>

</ol>