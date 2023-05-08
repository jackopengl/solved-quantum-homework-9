Download Link: https://assignmentchef.com/product/solved-quantum-homework-9
<br>



We will consider a generalization of Grover’s algorithm. Suppose that we are given the following.

<ul>

 <li>A, a quantum circuit.</li>

 <li>Basis vector |starti and quantum state |endi (i.e. norm 1) with A|starti = |end</li>

 <li>|endi = |<em>A</em>i + |<em>B</em>i with h<em>A </em>| <em>B</em>i = 0, h<em>A </em>| <em>A</em>i = <em>a</em>, and h<em>B </em>| <em>B</em>i = <em>b </em>= 1 − <em>a</em>.</li>

</ul>

Let us consider |<em>A</em>i as consisting of a superposition of “correct” outcomes of algorithm A.

Upon measuring |endi, the probability of observing |<em>A</em>i is <em>a</em>.

We assume that we have a basis (<em>ψ<sub>i</sub></em>)<em><sub>i</sub></em><sub>∈<em>I </em></sub>such that <em>I </em>= <em>A</em>∪<em>B </em>and a function <em>χ </em>: <em>I </em>→ {0<em>,</em>1} such that <em>χ</em>(<em>A</em>) = 1 and <em>χ</em>(<em>B</em>) = 0. Define

|Ψ(<em>α,β</em>)i = <em>α</em>|<em>A</em>i + <em>β </em>|<em>B</em>i

and note that |Ψ(1<em>,</em>1)i = |endi. Define G = A ◦ <em>D</em><sub>s </sub>◦ A<sup>† </sup>◦ <em>D<sub>A </sub></em>where <em>D<sub>A </sub></em>is a reflection operator for |<em>A</em>i and <em>D</em><sub>s </sub>is a reflection operator for |starti (use the phase shift <em>e<sup>iθ </sup></em>for both).

<ol>

 <li>Draw the circuits for both reflection operators and also write out the operators for them (e.g. <em>D</em><sub>0 </sub>= (<em>e<sup>iθ </sup></em>− 1)|0ih0| + <em>I </em>as in the usual Grover’s algorithm).</li>

 <li>Calculate G |Ψ(1<em>,</em>1)i and write your answer in the form |Ψ(<em>x,y</em>)i for some <em>x,y </em>(you should specify their values).</li>

 <li>Suppose that A works with probability 1<em>/</em>4 (i.e. <em>a </em>= 1<em>/</em>4). Show that taking <em>θ </em>= <em>π </em>(as in the usual Grover’s circuit) makes G ◦ A acting on |starti exact (i.e. it produces a correct answer with probability 1).</li>

 <li>Show that when A works with probability 1<em>/</em>2 there is a choice of <em>θ </em>so that G ◦ A acting on |starti is exact. What is the value of <em>e<sup>iθ </sup></em>in this case?</li>

</ol>