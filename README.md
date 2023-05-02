Download Link: https://assignmentchef.com/product/solved-cmpt360-assignment-5
<br>
<strong>Q1. </strong>Assume that a problem <em>A </em>cannot be solved in <em>O</em>(<em>n</em><sup>2</sup>) time. However, we can transform <em>A </em>into a problem <em>B </em>in <em>O</em>(<em>n</em><sup>2 </sup>log<em>n</em>) time, and then solve <em>B</em>, and finally transform the solution of <em>B </em>in <em>O</em>(<em>n</em>) time into a solution for <em>A</em>.

Prove or Disprove: The above approach shows that <em>B </em>cannot be solved asymptotically less than <em>O</em>(<em>n</em><sup>2</sup>) time.

<strong>Q2. </strong>Prove that Minimum Vertex Cover problem is NP-hard by reducing the NP-hard problem Maximum Independent Set.

<strong>Q3. </strong>Since finding a minimum vertex cover in a graph is known to be NP-hard, we want to find a vertex cover <em>S </em>that is not too large than a minimum vertex cover. We propose the following algorithm.

Step 1. Initialize <em>S </em>with an empty set.

Step 2. While there is an edge in <em>G</em>, randomly choose an edge (<em>a,b</em>) and insert <em>a </em>and <em>b </em>into <em>S</em>. Then delete the vertices <em>a </em>and <em>b</em>, and all the edges incident to <em>a </em>and <em>b</em>.

Step 3. Return <em>S</em>

Prove that the size of the set <em>S </em>returned by the algorithm can be at most twice the size of a minimum vertex cover of <em>G</em>.

<strong>Q4. </strong>You are give a social network of <em>n </em>students, where two students are connected if and only if they are friends. Consider the problem of finding a smallest set <em>S </em>of students from the network such that any student in the network is either in <em>S</em>, or a friend of someone who belongs to <em>S</em>.

Either give a polynomial-time algorithm for the problem, or show that the problem is NPhard by reducing the Minimum Vertex Cover problem.