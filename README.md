Download Link: https://assignmentchef.com/product/solved-dynamical-homework-4
<br>
<strong>1.1      Section 2.8 Problem 1.</strong>

Suppose we have <em>n &gt; </em>0 disjoint subsets of N, which we will denote as <em>A<sub>i </sub></em>for each 1 <em>≤ i ≤ n</em>. For now, suppose each <em>A<sub>i </sub></em>is a finite set. Let us take the union of these sets, <em>A </em>= <em>t<sup>n</sup><sub>i</sub></em><sub>=0</sub><em>A<sub>i</sub></em>. We have that,

<h2>X           1</h2>

<em>µ</em>(<em>A</em>) =

2<em>k k∈</em><em><sub>A</sub></em>

However, since the <em>A<sub>i </sub></em>are all disjoint, we have that each <em>k </em>is in one and only one <em>A<sub>i</sub></em>. Hence, we can re-index this summation as, 1 X <em>µ</em>(<em>A</em>) =

<em>k∈A</em><sub>1 </sub>or <em>k∈A</em><sub>2 </sub>or <em>… </em>or <em>k∈A<sub>n </sub></em>2<em>k</em>

Since each of these possibilities are disjoint, let us split it up into separate summations,

X 1            X 1                      X 1

<em>µ</em>(<em>A</em>) =            +            + <em>··· </em>


<em>k∈A</em>1 2<em>k          </em><em><sub>k</sub></em><em>∈A</em><sub>2 </sub>2<em>k                       </em><em><sub>k</sub></em><em>∈A<sub>n </sub></em>2<em>k</em>

= <em>µ</em>(<em>A</em><sub>1</sub>) + <em>µ</em>(<em>A</em><sub>2</sub>) + <em>··· </em>+ <em>µ</em>(<em>A<sub>n</sub></em>)

So we have covered the case where each <em>A<sub>i </sub></em>is finite. Now suppose at least one is infinite. Then we must also have that <em>A </em>is infinite and so <em>µ</em>(<em>A</em>) = <em>∞</em>. Observe we also have,

<em>n</em>

X

<em>µ</em>(<em>A<sub>i</sub></em>) = <em>µ</em>(<em>A</em><sub>1</sub>) + <em>µ</em>(<em>A</em><sub>2</sub>) + <em>··· </em>+ <em>∞ </em>+ <em>··· </em>+ <em>µ</em>(<em>A<sub>n</sub></em>)

<em>i</em>=1

= <em>∞</em>

Hence, we have that <em>µ</em>(<em>A</em>) = <em>µ</em>(<em>A</em><sub>1</sub>)+<em>µ</em>(<em>A</em><sub>2</sub>)+<em>···</em>+<em>µ</em>(<em>A<sub>n</sub></em>) once again and thus, <em>µ </em>is finitely additive.

Now suppose we have a countable number of sets <em>A<sub>i</sub></em>, where <em>A<sub>i </sub></em>= <em>{i}</em>. Then we have,

X

<em>µ</em>(<em>A<sub>i</sub></em>) = <em>µ</em>(<em>A</em><sub>1</sub>) + <em>µ</em>(<em>A</em><sub>2</sub>) + <em>···</em>

=

2<em>i i</em><sub>=1</sub>

= 1

However, if we consider <em>A </em>= <em>tA<sub>i</sub></em>, we have that <em>A </em>= N and hence is an infinite set. Thus, <em>µ</em>(<em>A</em>) = <em>∞ </em>and so,

<em>µ</em>(<em>A</em>) <em>6</em>= <sup>X</sup><em>µ</em>(<em>A<sub>i</sub></em>)

Thus, <em>µ </em>is not countably additive.

<strong>Problem 2.</strong>

Since <em>R </em>is a semi-ring, we have that <em>A  ∅ ∈ R </em>and,

<h2><em>A  ∅ </em>= <em>A</em></h2>

= <em>t</em><em>nj</em>=1<em>E</em><em>j</em>

for some disjoint sets <em>E<sub>j </sub>∈ R</em>. Moreover, since <em>K </em>= <em>∪K<sub>i </sub></em>with <em>K<sub>i </sub>∈ R </em>for every <em>i</em>, we can apply Proposition 2.7.1 and get,

<em>K </em><em>C<sub>k</sub></em>

where the sets <em>{C<sub>k</sub>} </em>are disjoint and in <em>R</em>. Now consider <em>K  A </em>using these above definitions. We have,

<em>K  A </em><em>  t</em><em>nj</em>=1<em>E</em><em>j</em>

= <em>t</em><em>∞k</em>=1<em>C</em><em>k  t</em><em>nj</em>=1<em>E</em><em>j</em>

Observe that for each <em>k</em>, the set <em>C<sub>k </sub> t<sup>n</sup><sub>j</sub></em><sub>=1</sub><em>E<sub>j</sub></em> is in <em>R</em>. Hence, we have that

<em>C</em><em>k  t</em><em>nj</em>=1<em>E</em><em>j</em> = <em>t</em><em>nj</em>=1<em>E</em><em>j</em>(<em>k</em>)

Note that for each <em>k</em>, we have that,

<em>C</em><em>k  t</em><em>nj</em>=1<em>E</em><em>j</em> <em>∩ A </em>= <em>t</em><em>nj</em>=1<em>E</em><em>j</em>(<em>k</em>) <em>∩ A</em>

= <em>∅</em>

Moreover, for <em>k</em>1 <em>6</em>= <em>k</em>2, since <em>C</em><em>k</em>1 <em>∩ C</em><em>k</em>2 = <em>∅</em>, then <em>t</em><em>nj</em>=1<em>E</em><em>j</em>(<em>k</em>1) <em>∩ t</em><em>jn</em>=1<em>E</em><em>j</em>(<em>k</em>2) and so <em>E<sub>j</sub><sup>k</sup></em><sup>1 </sup><em>∩ E<sub>i</sub><sup>k−</sup></em><sup>2 </sup>= <em>∅ </em>for any <em>i,j</em>.

Lastly, note that,

<em>K  A t A </em>= <em>t</em><em>∞k</em>=1 <em>t</em><em>nj</em>=1<em>E</em><em>j</em>(<em>k</em>) <em>t t</em><em>nj</em>=1<em>E</em><em>j</em>

= <em>K</em>

Hence,

<em>µ</em>(<em>K</em>) = <em>µ</em>(<em>K  A</em>) + <em>µ</em>(<em>A</em>)

<em>n t<sub>j</sub></em>

= <sup>X </sup><em>µ</em>

<em>k</em>=1

<em>∞ n</em>

= XX<em>µ</em>(<em>E</em><em>j</em>(<em>k</em>)) + <em>µ</em>(<em>A</em>)

<em>k</em>=1 <em>j</em>=1

Since <em>µ</em> for all <em>j,k</em>, we must have from the above derivation that <em>µ</em>(<em>A</em>) <em>≤ µ</em>(<em>K</em>). Moreover, we have that,

<em>K </em>= <em>∪<sub>i</sub>K<sub>i</sub></em>

= <em>t</em><em>kC</em><em>k</em>

So,

<em>µ</em>(<em>K</em>) = <em>µ</em>(<em>∪<sub>i</sub>K<sub>i</sub></em>)

= <em>µ</em>(<em>t<sub>k</sub>C<sub>k</sub></em>)

= <sup>X</sup><em>µ</em>(<em>C<sub>k</sub></em>)

<em>k</em>

<strong>Problem 5.</strong>

Suppose <em>µ </em>is countably additive. Since finite collections are countable, we must have that for any disjoint sets <em>A<sub>i</sub></em>, 1 <em>≤ i ≤ n </em>in <em>R</em>, we have that,

<em>n</em>

<em>µ</em>(<em>t</em><em>ni</em>=1<em>A</em><em>i</em>) = X<em>µ</em>(<em>A</em><em>i</em>)

<em>i</em>=1

Hence, <em>µ </em>is finitely additive. Moreover if we have a countably infinite collection disjoint of sets <em>B<sub>i </sub></em>where each <em>B<sub>i </sub>∈ R</em>, then since <em>µ </em>is countably additive, we have,

<em>∞</em>

<em>µ</em>(<em>t</em><em>∞i</em>=1<em>B</em><em>i</em>) = X<em>µ</em>(<em>B</em><em>i</em>)

<em>i</em>=1

which satisfies the definition of countable subadditivity.

Now assume <em>µ </em>is additive and countably subadditive.

<strong>1.2      Section 3.2 Problem 2.</strong>

Let <em>d ∈ {x</em><sub>1</sub><em>.x</em><sub>2</sub><em>x</em><sub>3</sub><em>x</em><sub>4 </sub><em>|x</em><sub>1 </sub><em>∈ {</em>1<em>,</em>2<em>,…,</em>9<em>} </em>and <em>x</em><sub>2</sub><em>,x</em><sub>3</sub><em>,x</em><sub>4 </sub><em>∈ {</em>0<em>,</em>1<em>,</em>2<em>,…,</em>9<em>}}</em>. Then <em>d </em>is the set of numbers between 1<em>.</em>000 and 9<em>.</em>999 (inclusive) that have terminating decimal expansion of length 4. Now suppose the decimal representation of 3<em><sup>n </sup></em>starts with <em>d · </em>10<sup>3</sup>. Then for some integer <em>k ≥ </em>0,

<em>d · </em>10<em><sup>k </sup>≤ </em>3<em><sup>n </sup>&lt; </em>(<em>d </em>+ 0<em>.</em>001) <em>· </em>10<em><sup>k</sup></em>

Thus,

log<sub>10</sub>(<em>d · </em>10<em><sup>k</sup></em>) <em>≤ </em>log<sub>10 </sub>3<em><sup>n </sup>&lt; </em>log<sub>10</sub>((<em>d </em>+ 0<em>.</em>001) <em>· </em>10<em><sup>k</sup></em>

which gives us,

log<sub>10 </sub><em>d ≤ n</em>log<sub>10 </sub>3 <em>− k &lt; </em>log<sub>10</sub>(<em>d </em>+ 0<em>.</em>001)

and finally,

log<sub>10 </sub><em>d ≤ n</em>log<sub>10 </sub>3 (mod 1) <em>&lt; </em>log<sub>10</sub>(<em>d </em>+ 0<em>.</em>001)

But this is the same as saying that, letting <em>α </em>= log<sub>10 </sub>3,

<em>R</em>

Since 0 <em>≤ </em>log<sub>10 </sub><em>d &lt; </em>1 based on our definition of <em>d </em>and <em>α </em>is irrational, we can apply

Theorem 3.2.3. Thus, there are infinitely many integers <em>n </em>such that <em>R </em>0<em>.</em>001)). Hence, there are infinitely many powers of 3 that start with 1984.

<strong>1.3      Section 3.4 Problem 1.</strong>

We have that the collection of left-closed, right-open dyadic intervals form a sufficient semi-ring for (R<em>,L,λ</em>). Suppose <em>I ∈ C</em>. Then we write <em>I </em>= [<em>k/</em>2<em><sup>i</sup>,</em>(<em>k </em>+ 1)<em>√ /</em>2<em><sup>i</sup></em>) for integers <em>k,i</em>

with <em>i,k ∈ </em>Z. We have <em>µ </em><em>I       </em><sub>2 </sub>. Moreover, we have <em>T<sup>−</sup></em><sup>1</sup>(<em>x</em>) = <em>x ±               x</em><sup>2 </sup>+ 4 for <em>x 6</em>= 0 and

<em>T<sup>−</sup></em><sup>1</sup>(0) = 0. This gives us, <em><sup>−</sup></em><sup>1        </sup>                <em><sup>ii </sup></em>q           <sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4 [

<em>T         </em>(<em>I</em>) = <em>k/</em>2 +                      + 4<em>,</em>(<em>k </em>+ 1)<em>/</em>2 +        (<em>k </em>+ 1)

<em>k/</em>2<em><sup>i </sup>− </em>q<em>k</em><sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4<em>,</em>(<em>k </em>+ 1)<em>/</em>2<em>i − </em>q(<em>k </em>+ 1)2<em>/</em>22<em>i </em>+ 4

<em>T<sup>−</sup></em><sup>1</sup>(<em>I</em>) is a finite union of intervals and is hence measurable.

Observe that q(<em>k </em>+ 1)<sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4 <em>&gt; </em>q(<em>k </em>+ 1)<sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>= (<em>k</em>+1)<em>/</em>2<em><sup>i </sup></em>and <sup>q</sup><em>k</em><sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4 <em>&gt; </em><sup>q</sup><em>k</em><sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>= <em>k/</em>2<em><sup>i</sup></em>. Hence, <em>T<sup>−</sup></em><sup>1</sup>(<em>I</em>) is a disjoint union and, <em>µT</em><em>−</em>1(<em>I</em>) = <em>µk/</em>2<em>i </em>+ q<em>k</em>2<em>/</em>22<em>i </em>+ 4<em>,</em>(<em>k </em>+ 1)<em>/</em>2<em>i </em>+ q(<em>k </em>+ 1)2<em>/</em>22<em>i </em>+ 4


<em>µk/</em>2<em><sup>i </sup>− </em>q<em>k</em><sup>2</sup><em>/</em>2                                   <em>i </em>q                         2<em>/</em>22<em>i </em>+ 4

2<em>i </em>+ 4<em>,</em>(<em>k </em>+ 1)<em>/</em>2 <em>−         </em>(<em>k </em>+ 1)

= (<em>k </em>+ 1)<em>/</em>2<em><sup>i </sup></em>+ <sup>q</sup>(<em>k </em>+ 1)<sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4 <em>− </em>(<em>k/</em>2<em><sup>i </sup></em>+ <sup>q</sup><em>k</em><sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4)


(<em>k </em>+ 1)<em>/</em>2<em><sup>i </sup>− </em><sup>q</sup>(<em>k </em>+ 1)<sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4 <em>− k/</em>2<em><sup>i </sup></em>+ <sup>q</sup><em>k</em><sup>2</sup><em>/</em>2<sup>2<em>i </em></sup>+ 4

= (<em>k </em>+ 1)<em>/</em>2<em><sup>i </sup>− k/</em>2<em><sup>i </sup></em>+ (<em>k </em>+ 1)<em>/</em>2<em><sup>i </sup>− k/</em>2<em><sup>i</sup></em>

= 2(<em>k </em>+ 1)<em>/</em>2<em><sup>i </sup>− </em>2<em>k/</em>2<em><sup>i</sup></em>

= (<em>k </em>+ 1)<em>/</em>2<em><sup>i−</sup></em><sup>1 </sup><em>− k/</em>2<em><sup>i−</sup></em><sup>1</sup>

= 1<em>/</em>2<em>i−</em>1

<strong>Problem 2.</strong>

Suppose (<em>X,S,µ</em>) is a <em>σ</em>-finite measure-space and <em>T </em>: <em>X → X </em>is measure-preserving. Fix <em>X</em><sub>0 </sub><em>∈ S</em>(<em>X</em>) with <em>T<sup>−</sup></em><sup>1</sup>(<em>X</em><sub>0</sub>) = <em>X</em><sub>0</sub>.We want to show that the system (<em>X</em><sub>0</sub><em>,S</em>(<em>X</em><sub>0</sub>)<em>,µ,T</em>) is a measure-preserving dynamical system. That is (<em>X</em><sub>0</sub><em>,S</em>(<em>X</em><sub>0</sub>)<em>,µ</em>) is a <em>σ</em>-finite measure space and <em>T </em>: <em>X</em><sub>0 </sub><em>→ X</em><sub>0 </sub>is a measure preserving transformation.

By Proposition 2.5.1, since <em>X</em><sub>0 </sub><em>⊂ X </em>is in <em>S</em>, we have that <em>S</em>(<em>X</em><sub>0</sub>) = <em>{A </em>: <em>A ⊂ X</em><sub>0 </sub>and <em>X</em><sub>0 </sub><em>∈ S} </em>is a <em>σ</em>-algebra on <em>X</em><sub>0</sub>. Since the original measure space was <em>σ</em>-finite, there exist a sequence of measurable sets <em>A<sub>n </sub></em>of finite measure such that,

<em>∞</em>

<em>X </em>= [ <em>A</em><em>n</em>

<em>n</em>=1

Since <em>X</em><sub>0 </sub>is in the collection of measurable sets and is a subset of <em>X</em>, we can remove sets from the sequence <em>B<sub>n</sub></em>, creating a new sequence <em>B<sub>n </sub></em>such that,

<em>∞</em>

<em>X</em>0 = [ <em>B</em><em>n</em>

<em>n</em>=1 Hence, the new measure space is <em>σ</em>-finite as well.

<strong>Problem 3.</strong>

Let (<em>X,S,µ</em>) be a <em>σ</em>-finite measure space and let <em>X</em><sub>0 </sub><em>∈ S</em>(<em>X</em>) with <em>µ</em>(<em>XX</em><sub>0</sub>) = 0. Suppose there exists a transformation <em>T</em><sub>0 </sub>so that (<em>X</em><sub>0</sub><em>,S</em>(<em>X</em><sub>0</sub>)<em>,µ,T</em><sub>0</sub>) is a measure-preserving dynamical system. Since the original measure space is <em>σ</em>-finite

<strong>Problem 4.</strong>

Suppose (<em>X,S,µ,T</em>) is a measure-preserving dynamical system.